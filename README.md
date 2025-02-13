# Analysis-of-Police-Stop-Search-Data-in-the-UK-2019-
How to run the program: 
The entire code for the program has been written using python 3.9.6. The codes have been broken into modules namely: 

•	**APK_module**: This module creates a GUI and likewise interacts with other modules to produce the charts. 

•	**API_Module**: This module extracts Stop & Search data via API. 

•	**Data Cleaning module**: Cleans the datasets and extracts additional features from the datasets 

•	**Visualization module**: This module contains functions that generate visual charts from the dataset. 

The entire program runs fully from the APK module. 

To run the entire program, run the APK module either from the command prompt terminal (by double clicking the APK module) or from the python terminal. The charts will Open in a new window, close each figure to generate the next figure. NOTE THAT IT MIGHT TAKE A WHILE BEFORE CHARTS GET DISPLAYED. 
Dependency Information: 
The dependency library used are: pandas, matplotlib, seaborn and pywaffle. These libraries can be installed on your local system by using the pip command in the command prompt terminal 


# 🚔 UK Police Stop and Search Data Analysis

## **🔍 Overview**
This project analyzes **UK police stop-and-search data** to uncover trends, assess the impact of policing strategies, and provide data-driven insights. Using **Python and visualization tools**, this analysis answers key questions on **age distribution, geographical trends, and policy implications**.

## **📌 Objectives**
✅ Retrieve **stop-and-search records** via API or pre-downloaded datasets.  
✅ Clean, preprocess, and analyze the **data for key insights**.  
✅ **Visualize trends** using **Matplotlib & Seaborn**.  
✅ Investigate **COVID-19’s impact on stop-and-search numbers**.  
✅ Develop a **modular, reusable data science pipeline**.

---

## **📊 Key Research Questions**
1 **Which police force conducted the highest number of stop-and-search operations?**

2 **How does the frequency of stop-and-search vary by police force?**

3 **What is the gender distribution of individuals stopped and searched?**

4 **Which age groups are most frequently searched?**

5 **Are certain ethnic groups more likely to be stopped and searched?**

^ **What time of day do most stop-and-search incidents occur? Was there a change in stop-and-search patterns during major events (e.g., COVID-19 lockdowns)?**  

---

## **🛠️ Tech Stack**
- **Programming:** Python (`pandas`, `numpy`, `requests`)  
- **Data Visualization:** `matplotlib`, `seaborn`, `pywaffle`  
- **Data Retrieval:** `requests` (for API calls), static datasets  
- **Testing & Deployment:** Unit testing, modular pipelines  



---

## **🗂️ Data Processing Workflow**
1️⃣ **Data Retrieval**  
   - Fetch data from the **UK Police API** or **pre-downloaded CSVs**.  
   - Handle **missing values and inconsistencies**.  

2️⃣ **Exploratory Data Analysis (EDA)**  
   - Aggregate stop-and-search data by **age, gender, and ethnicity**.  
   - Compare search patterns **before and after COVID-19 lockdowns**.  

3️⃣ **Data Visualization**  
   - 📊 **Bar Charts** – Police force comparison.  
   - 📈 **Time-Series Plots** – Trend analysis.  
   - 🎭 **Waffle Charts** – Legal justifications for searches.  
   - 🎨 **Stacked Bar Charts** – Search outcomes and clothing removal.  

4️⃣ **Testing & Validation**  
   - **Unit tests** ensure pipeline integrity.  
   - **Cross-validation** confirms **API vs. static data consistency**.  

---

📌 **Question Answered:** Which police force conducted the most stop-and-searches?  
✅ **Finding:** Some police forces conducted significantly more stop-and-search operations than others, suggesting regional variations in enforcement policies.

---

## 2️⃣ Gender and Age Distribution
📌 **Question Answered:** Who is stopped the most based on gender and age?  
✅ **Finding:**  
- Males were searched significantly more than females, indicating a gender disparity.  
- Young adults (ages 18-24) were the most frequently searched group, raising questions about targeted demographics.

---

## 3️⃣ Search Methods & Outcomes
📌 **Question Answered:** Is there a link between more invasive searches and specific outcomes?  
✅ **Finding:**  
- People who had more than their outer clothing removed showed varying search outcomes, with some leading to further action while others did not.

---

## 4️⃣ Ethnicity & Stop-and-Search Discrepancies
📌 **Question Answered:** How does self-reported ethnicity compare to officer-defined ethnicity?  
✅ **Finding:**  
- Officer-defined ethnicity sometimes differs from self-defined ethnicity, indicating potential inconsistencies or biases in police classification.

---

## 5️⃣ Search Type Distribution
📌 **Question Answered:** Were more people or vehicles searched?  
✅ **Finding:**  
- The majority of stop-and-searches were **"Person Searches"**, with **Vehicle Searches** being much less common.

---

## 6️⃣ Most Common Legal Justifications
📌 **Question Answered:** Which laws were most frequently cited for stop-and-searches?  
✅ **Finding:**  
- Certain legislation powers were used disproportionately(Drug misuse act), suggesting reliance on specific laws for justifying searches.

---

## 7️⃣ Searches by Hour of the Day
📌 **Question Answered:** When do most stop-and-searches occur?  
✅ **Finding:**  
- Stop-and-search activity fluctuated throughout the day, with peak search times appearing at specific hours, potentially indicating patterns in policing behavior.

---

🔍 **Conclusion:**  
The data suggests notable variations in stop-and-search activity across different police forces, demographic groups, and legal justifications. These insights can help inform discussions around policing policies and potential areas for reform.





## **🗂️ Data Processing Workflow**
1️⃣ **Data Retrieval**  
   - Fetch data from the **UK Police API** or **pre-downloaded CSVs**.  
   - Handle **missing values and inconsistencies**.  

2️⃣ **Exploratory Data Analysis (EDA)**  
   - Aggregate stop-and-search data by **age, gender, and ethnicity**.  
   - Compare search patterns **before and after COVID-19 lockdowns**.  

3️⃣ **Data Visualization**  
   - 📊 **Bar Charts** – Police force comparison.  
   - 📈 **Time-Series Plots** – Trend analysis.  
   - 🎭 **Waffle Charts** – Legal justifications for searches.  
   - 🎨 **Stacked Bar Charts** – Search outcomes and clothing removal.  

4️⃣ **Testing & Validation**  
   - **Unit tests** ensure pipeline integrity.  
   - **Cross-validation** confirms **API vs. static data consistency**.  

---

## **🚀 Installation & Usage**
### **🔧 Setup**
1️⃣ Clone the repository:
```bash
git clone https://github.com/Oluboye123/uk-police-stop-search.git
cd uk-police-stop-search

pip install -r requirements.txt

python stop_and_search.py



