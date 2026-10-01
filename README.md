# 📊 HR Analytics

An end-to-end **HR Analytics and Exploratory Data Analysis (EDA)** project focused on analyzing employee data, identifying workforce patterns, and generating actionable insights using **Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook, and Excel**.

The project combines detailed Python-based analysis with an interactive Excel dashboard to understand employee demographics, workforce distribution, compensation, performance, and other HR-related patterns.

---

## 📌 Project Overview

Human Resources departments generate large amounts of employee data. Analyzing this data can help organizations understand their workforce, identify patterns, and support data-driven HR decisions.

This project performs an exploratory analysis of an HR dataset and presents the findings through:

* 🐍 Python-based data analysis
* 📓 Jupyter Notebook
* 📊 Exploratory Data Analysis (EDA)
* 📈 Data visualizations
* 📑 Excel HR Analytics Dashboard
* 🔍 Deep-dive analysis of HR-related variables

---

## 🎯 Objectives

The main objectives of this project are to:

1. Understand the structure and characteristics of the HR dataset.
2. Perform data cleaning and preprocessing.
3. Analyze employee demographics and workforce distribution.
4. Explore relationships between different HR variables.
5. Identify trends and patterns in employee data.
6. Perform statistical and exploratory analysis.
7. Create meaningful visualizations.
8. Build an HR Analytics dashboard in Excel.
9. Generate insights that can support HR decision-making.

---

## 🗂️ Repository Structure

```text
HR-Analytics/
│
├── 📊 HR_Analytics_EDA_Dashboard.xlsx
│   └── Excel-based HR Analytics dashboard and EDA
│
├── 📦 hr_analytics_dataset.zip
│   └── HR analytics dataset
│
├── 📓 hr_analytics_deep_dive.ipynb
│   └── Detailed Python-based analysis
│
└── 📄 README.md
    └── Project documentation
```

---

## 🛠️ Technologies Used

| Technology          | Purpose                         |
| ------------------- | ------------------------------- |
| 🐍 Python           | Data analysis and preprocessing |
| 🐼 Pandas           | Data manipulation and analysis  |
| 🔢 NumPy            | Numerical operations            |
| 📊 Matplotlib       | Data visualization              |
| 📈 Seaborn          | Statistical visualization       |
| 📓 Jupyter Notebook | Interactive analysis            |
| 📗 Microsoft Excel  | Dashboard and reporting         |

---

## 🔄 Project Workflow

```text
                HR Dataset
                    │
                    ▼
          Data Loading & Inspection
                    │
                    ▼
             Data Cleaning
                    │
                    ▼
          Exploratory Data Analysis
                    │
          ┌─────────┴─────────┐
          ▼                   ▼
   Statistical Analysis   Data Visualization
          │                   │
          └─────────┬─────────┘
                    ▼
             Deep-Dive Analysis
                    │
                    ▼
             HR Insights
                    │
                    ▼
          Excel Analytics Dashboard
```

---

# 🔍 Exploratory Data Analysis

The project explores different aspects of the employee dataset, including areas such as:

### 👥 Employee Demographics

Analysis of employee characteristics and workforce composition.

Potential areas include:

* Age distribution
* Gender distribution
* Employee distribution
* Marital status
* Education
* Job roles

### 🏢 Workforce Analysis

Analysis of how employees are distributed across organizational units.

Examples:

* Departments
* Job roles
* Job levels
* Business units
* Work locations

### 💰 Compensation Analysis

Exploration of employee compensation-related variables.

Possible analysis includes:

* Salary distribution
* Salary by department
* Salary by job role
* Salary by experience
* Compensation differences across employee groups

### 📈 Performance Analysis

Analysis of employee performance and related HR variables.

Possible areas include:

* Performance ratings
* Job satisfaction
* Work-life balance
* Training
* Performance trends

### 🚪 Attrition Analysis

Employee attrition can be explored to understand workforce retention patterns.

Analysis may include relationships between attrition and:

* Age
* Department
* Job role
* Salary
* Job satisfaction
* Years at company
* Overtime
* Work-life balance
* Performance

---

# 📊 Excel HR Analytics Dashboard

The repository includes:

**`HR_Analytics_EDA_Dashboard.xlsx`**

The Excel workbook is designed to provide a visual overview of HR-related metrics and patterns.

The dashboard can be used to explore:

* Employee workforce metrics
* Demographic distributions
* Department-level information
* Job-role analysis
* Compensation patterns
* Employee performance
* Attrition-related information

---

# 📓 Deep-Dive Analysis

The repository also contains:

**`hr_analytics_deep_dive.ipynb`**

This notebook contains the detailed Python analysis of the HR dataset.

The notebook follows a typical data-analysis workflow:

```text
Import Libraries
       ↓
Load Dataset
       ↓
Understand Data
       ↓
Data Cleaning
       ↓
Descriptive Statistics
       ↓
Univariate Analysis
       ↓
Bivariate Analysis
       ↓
Multivariate Analysis
       ↓
Visualization
       ↓
Deep-Dive Analysis
       ↓
Insights
```

---

# 📈 Types of Analysis

The project can include the following analytical techniques:

### Univariate Analysis

Analyzing individual variables.

Examples:

```text
Age distribution
Salary distribution
Employee counts
Department distribution
```

### Bivariate Analysis

Analyzing relationships between two variables.

Examples:

```text
Salary vs Experience
Age vs Attrition
Department vs Salary
Job Role vs Performance
```

### Multivariate Analysis

Analyzing relationships between multiple variables.

Examples:

```text
Department + Job Role + Salary
Age + Experience + Attrition
Performance + Satisfaction + Attrition
```

---

# 📊 Key Business Questions

The analysis is designed to help answer questions such as:

### Workforce

* How many employees are present in the organization?
* How are employees distributed across departments?
* Which job roles have the largest employee populations?

### Compensation

* How is salary distributed among employees?
* How does compensation vary across departments?
* How does experience relate to compensation?

### Employee Experience

* What factors are associated with employee satisfaction?
* How does work-life balance vary across employees?
* Are there differences in satisfaction across departments or roles?

### Attrition

* What patterns can be observed among employees who leave?
* Which employee characteristics are associated with attrition?
* How do job satisfaction and overtime relate to attrition?
* Does employee tenure appear to be associated with attrition?

---

# 💡 Insights

The project is intended to transform raw employee data into meaningful HR insights.

Examples of insights that can be generated include:

* Workforce distribution patterns
* Department-level differences
* Compensation patterns
* Employee satisfaction patterns
* Performance relationships
* Potential attrition-related patterns
* Employee tenure trends

> **Note:** Specific numerical findings should be taken directly from the analysis notebook and dashboard rather than assumed from the project description.

---

# 🚀 How to Run the Project

## 1. Clone the Repository

```bash
git clone https://github.com/DhanaVazanth/HR-Analytics.git
```

## 2. Navigate to the Project

```bash
cd HR-Analytics
```

## 3. Extract the Dataset

Extract:

```text
hr_analytics_dataset.zip
```

into the project directory.

## 4. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter openpyxl
```

## 5. Start Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
hr_analytics_deep_dive.ipynb
```

and execute the notebook cells.

---

# 📦 Project Files

### `hr_analytics_dataset.zip`

Contains the dataset used for the HR analysis.

### `hr_analytics_deep_dive.ipynb`

Contains the Python implementation of the exploratory and deep-dive analysis.

### `HR_Analytics_EDA_Dashboard.xlsx`

Contains the Excel-based HR Analytics dashboard and supporting analysis.

---

# 🎓 Skills Demonstrated

This project demonstrates practical skills in:

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis
* Descriptive Statistics
* Statistical Analysis
* Data Visualization
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Microsoft Excel
* Dashboard Development
* Business Analytics
* HR Analytics
* Data Storytelling

---

# 🔮 Future Improvements

Potential improvements to the project include:

* [ ] Add an interactive Power BI dashboard
* [ ] Perform advanced statistical testing
* [ ] Build an employee attrition prediction model
* [ ] Perform feature engineering
* [ ] Apply machine learning classification algorithms
* [ ] Add employee segmentation using clustering
* [ ] Perform correlation and feature-importance analysis
* [ ] Add automated reporting
* [ ] Deploy the dashboard as a web application
* [ ] Add a complete data dictionary
* [ ] Add automated data-quality checks

---

# 👨‍💻 Author

**Dhana Vasanth**

Data Science | Data Analytics | Machine Learning

---

# ⭐ Project

If you find this project useful, consider giving the repository a ⭐ on GitHub.

**Repository:**
https://github.com/DhanaVazanth/HR-Analytics
