# Data Analyst Salary Trends A Cluster Analysis of Technology Sector Compensation (R code)

***Analyzing Salary Trends Across Various Technologies Using Generalized Additive Models (GAM)***

Analyzed salary trends for data analysts using R, applying GAM for trend separation and AGNES clustering for technology grouping. Used feature engineering for keyword extraction and ggplot2 for visualization. Demonstrated skills in data wrangling, statistical modeling, and trend analysis.


This project analyzes **salary trends in the data analytics job market** and quantifies how different technologies influence earnings over time. Using **Generalized Additive Models (GAM)** and **clustering techniques**, the study uncovers insights into the most valuable technical skills and their impact on salary trends.  

---

## **Project Aim**  
The goal of this project is to analyze **salary trends for data analysts** and examine how different technologies affect earnings. By leveraging statistical modeling and clustering, we aim to:  

- Identify the **baseline salary trend** over time.  
- Measure the **impact of specific technologies** (SQL, Python, Power BI, Tableau, etc.) on salary levels.  
- Cluster technologies based on salary trends to **uncover broader industry patterns**.  
- Provide **actionable insights** for professionals, recruiters, and industry decision-makers.  

---

## **Technical Skills Demonstrated**  
- **Data Preprocessing & Feature Engineering**: Cleaning and transforming raw job listing data for analysis.  
- **Exploratory Data Analysis (EDA)**: Identifying salary trends and distribution patterns.  
- **Clustering Analysis**: Applying **hierarchical clustering** to group technologies with similar salary patterns.  
- **Generalized Additive Modeling (GAM)**: Capturing **non-linear salary trends** over time.  
- **Data Visualization**: Creating **trend charts and cluster visualizations** for insight extraction.  

---

## **Files in This Repository**  
| File | Description |
|------|------------|
| `Analysis of Technology Sector Compensation.ipynb` | Jupyter Notebook containing the full analysis workflow. |
| `gsearch_jobs.csv` | Raw dataset containing job postings and salary data. |

## **Dataset**  
This dataset consists of **data analyst job postings** scraped from Google search results, including:  

- **Job title, company name, and location**  
- **Salary details (hourly, annual, minimum, and maximum)**  
- **Required skills and technologies (SQL, Python, Power BI, etc.)**  
- **Date posted and job description**  

---

## How to Run This Project  
1. **Clone the repository**  
   ```bash
   git clone https://github.com/JordanConallLuthaisWright/Analysis of Technology Sector Compensation.git
   ```
2. **Navigate to the project directory**
   ```bash
   cd Analysis of Technology Sector Compensation
   ```
3. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
   ```
4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
5. Open and run `Analysis of Technology Sector Compensation.ipynb`

---

## **Business Scenario**  
This project investigates how different technologies influence **salary trends in the data analytics job market**. Key questions include:  

- **Which skills are associated with higher salaries?**  
- **Are traditional BI tools (Power BI, Tableau, Excel) still competitive?**  
- **How do salaries change for roles requiring SQL vs. SQL + Python?**  
- **What are the emerging trends in data analytics compensation?**  

By answering these questions, **professionals can identify high-value skills**, and **recruiters can optimize hiring strategies**.

---

## **Methodology & Technical Implementation**  

### **1. Data Preprocessing & Feature Engineering**  
- Extracted **keywords from job descriptions** to identify required skills.  
- Removed **unnecessary columns** to focus on salary-related attributes.  
- Converted **categorical variables into binary indicators** for analysis.  

### **2. Clustering Analysis**  
- Applied **hierarchical clustering** to identify **technology groups with similar salary patterns**.  
- Used **the Elbow Method** to determine the **optimal number of clusters**.  
- **Visualized cluster distributions** to interpret salary trends effectively.  

### **3. Generalized Additive Modeling (GAM)**  
- Modeled **salary evolution over time** using a **smooth baseline curve**.  
- Included **linear interaction terms** to evaluate **the impact of technologies on salaries**.  
- **Generated confidence intervals** to assess **salary trend uncertainty**.  

### **4. Key Findings & Insights**  
- **SQL remains stable**, but its **salary potential increases** when combined with **Python and cloud-based tools**.  
- **BI-focused roles (Power BI, Tableau) show salary volatility**, suggesting **changing market demand**.  
- **SQL + JavaScript + HTML skills exhibit strong salary growth**, highlighting **the rise of web-based data analytics**.  
- **Salaries for traditional analytics roles (SQL + Excel) may be stagnating**, indicating **a need for additional technical expertise**.  

---

## **Key Learnings & Applications**  
This project reinforced the importance of:  

- **Adapting to industry shifts** – Traditional **BI tools need supplementary coding skills** to stay competitive.  
- **Leveraging web-based analytics** – **SQL + JavaScript + HTML** is emerging as a **high-demand skillset**.  
- **Understanding salary trends** – Salary growth correlates with **cloud, web technologies, and automation skills**.  

### **Potential Future Work:**  
- **Expanding the dataset** to analyze **salary trends by region or industry**.  
- **Predictive modeling** to forecast **future salary trends based on job posting frequency**.  
- **Comparative analysis** between **full-time vs. freelance data analyst roles**.  

---

## **Contact & Contributions**  
Feel free to explore and contribute. If you have any suggestions, reach out or submit a pull request.  

- **Email**: [jordan.c.l.wright@gmail.com](mailto:jordan.c.l.wright@gmail.com)  

---

### **Author:** Jordan  
[GitHub Profile](https://github.com/JordanConallLuthaisWright)


