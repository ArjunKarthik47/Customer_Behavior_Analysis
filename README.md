## 📊 Customer Shopping Behavior Analysis
End-to-end data analytics project analyzing customer shopping behavior using Python, SQL, and Power BI. Includes data cleaning, EDA, feature engineering, SQL business insights, dashboard development. Perfect for showcasing full-stack data analytics skills from data preparation to storytelling.

## 📌 Overview
This project analyzes customer shopping behavior using transactional data. It covers the full data analytics workflow—loading data in Python, performing exploratory data analysis (EDA), cleaning the dataset, executing SQL queries using PostgreSQL/MySQL/SQL Server, building an interactive Power BI dashboard, generating insights, and preparing a final report and presentation using Gamma.

The goal is to identify trends, purchasing patterns, customer segments, and factors influencing spending and ratings.

---

### 📂 Dataset

- **Name**: Customer Shopping Behavior Dataset
- **Rows**: ~3,900 transactions
- **Columns**: 18 features (customer demographics, product details, spending, review ratings, discount usage, shipping type, etc.)
- **Source**: Provided internally for academic/project work (or publicly available if applicable)

Key fields include:  
`Customer ID, Age, Gender, Category, Purchase Amount, Location, Payment Method, Previous Purchases, Review Rating, Discount Applied, Item Purchased, etc.`

---

### 🛠 Tools & Technologies

**Programming & Analysis**
- Python: pandas, numpy, matplotlib/seaborn (EDA & cleaning)

**Databases**
- **PostgreSQL / MySQL / SQL Server**
  - For running SQL queries, joins, aggregations, KPIs

**Visualization & Reporting**
- **Power BI**: Interactive dashboard
- **Gamma**: For creating automated slide decks (PPT)
- **Microsoft Word / Google Docs**: Final analytical report

---

### 🧭 Project Steps

**1. Load Dataset (Python)**
- Import CSV using pandas
- Check data shape, types, missing values
- Generate initial descriptive statistics

**2. Exploratory Data Analysis (EDA)**
- Univariate and bivariate analysis
- Visualizations: histograms, bar charts, boxplots, heatmaps
- Insights on demographics, categories, spending trends

**3. Data Cleaning**

- Handle missing values
- Remove duplicates
- Convert data types
- Standardize categorical values
- Feature engineering (age groups, purchase scores, etc.)

**4. SQL Data Processing**
- Load cleaned dataset into SQL database
  - Run advanced SQL queries such as:
  - Top categories
  - Customer segments
  - Average purchase amount per location
  - Discount impact analysis
  - Frequency & repeat purchase trends

**5. Dashboard Creation (Power BI)**
- KPI cards (Total Purchase Amount, Avg Rating, Repeat Score)
- Charts: Category-wise sales, Age groups, Gender split, Locations
- Slicers: Category, Gender, Payment Method, Location, Season
- Interactive visuals for quick business insights

**6. Report Preparation**
- Summary of findings
- Insights from EDA
- SQL-driven metrics
- Visualizations from Power BI
- Actionable recommendations

**7. Presentation (PPT)**
- Automated slide deck with visuals
- Business-friendly summary
- Storytelling using insights

---

**📈 Dashboard Preview**
<img width="1114" height="617" alt="image" src="https://github.com/user-attachments/assets/c4327fc0-3604-4ef9-b253-c4aa4ca7aa3f" />


**📝 Key Results & Insights**
- Identified top-performing product categories
- Observed purchase trends by age, gender, location
- Found correlation between discounts and higher purchase frequency
- Recognized repeat purchase patterns using SQL aggregations
- Created interactive visuals enabling stakeholder decision-making

---

## ▶️ How to Run the Project
**1. Clone the Repository**
```
git clone https://github.com/your-username/customer-shopping-behavior-analysis.git
cd customer-shopping-behavior-analysis
```
**2. Install Python Dependencies**
```
pip install -r requirements.txt
```
**3. Run the Notebook**

Open Jupyter Notebook or VS Code and run:  
```
customer_behavior_analysis.ipynb
```
**4. Set Up the Database**
- Install PostgreSQL/MySQL/SQL Server
- Import SQL file or use the Python script to load data
- Run SQL queries from the `/sql_queries/` folder

**5. Open Power BI Dashboard**
- Download Power BI Desktop
- Open the file:
```
dashboard.pbix
```
**6. View the Final Report**
- Go to `/report/` folder
- Open the PDF or DOCX report

**7. Open the PPT**
- Access `/presentation/` folder
- View the PPT

---

## 📁 Repository Structure
```
📦 Customer-Shopping-Behavior-Analysis
 ┣ 📂 data
 ┣ 📂 python_notebooks
 ┣ 📂 sql_queries
 ┣ 📂 power_bi
 ┣ 📂 report
 ┣ 📂 presentation
 ┣ 📜 README.md
 ┣ 📜 requirements.txt
```

---

**🤝 Contributing**

Pull requests are welcome. For major changes, please open an issue first to discuss.

---

**📧 Contact**

For queries or collaboration:  
Arjun Karthik  
Email: thakurarjunkarthiksingh@gmail.com  
LinkedIn: https://www.linkedin.com/in/arjunkarthiksingh/
