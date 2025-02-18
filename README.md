# Data Analytics and Visualization

This repository contains scripts and datasets used for Data Analytics and Visualization assignments. Each assignment includes data processing, statistical analysis, and visualization tasks performed on different datasets.

---

## Assignments

<details>
  <summary><strong>Assignment 1: State Wise Udyam Registration Analysis (R)</strong></summary>

### **Description**
This assignment focuses on analyzing the **State Wise Udyam Registration Details** dataset from the **Ministry of Micro, Small & Medium Enterprises (MSME)** Udyam Registration platform. The analysis covers data processing, statistical analysis, and visualization.

### **Dataset**
The dataset includes six key fields:
- **Micro**
- **Small**
- **Medium**
- **Total Udyam**
- **IMEs (UAP)**
- **Total MSMEs**

 Dataset Links:
- [Udyam Registration Dashboard](https://dashboard.msme.gov.in/Udyam_Statewise.aspx)
- [Udyam Registration on Data.gov.in](https://www.data.gov.in/catalog/udyam-registration-msme-registration)

### **Features & Functionality**
✅ **Data Import and Preprocessing**
- Reads the dataset from a CSV file.
- Displays raw data.
- Removes the last row (Total) to avoid skewing analysis.
- Converts numeric columns to integer format after removing commas.

✅ **Descriptive Statistics Calculation**
- Computes **Mean, Median, Variance, and Standard Deviation** for numerical columns.
- Displays structured summary statistics.

✅ **Correlation Analysis**
- Computes correlation between fields.
- Generates and prints a **Correlation Matrix** to understand interdependencies.

### **How to Run the Code**
```bash
git clone <repository-url>
```
1. Open **R environment** or **RStudio**.
2. Load the necessary package:
```r
library(dplyr)
```
3. Run the script in **R**.
</details>

---

<details>
  <summary><strong>Assignment 2: R-Based Data Analysis and Visualization (Google Colab)</strong></summary>

### **Overview**
This assignment involves **data analysis and visualization using R**. The notebook is implemented in **Google Colab**, making it easy to run without requiring local installations.

### **How to Run the Code in Google Colab**
1. Open the following Google Colab link:  
    [Open DAV2 Notebook in Google Colab](https://colab.research.google.com/drive/1ulOiaGxeQixOnPu624Sq7v9t_PuIOuYS#scrollTo=OmlPSImyKh6g)
2. Click on **"Run All"** to execute all cells sequentially.
3. Analyze the outputs, visualizations, and insights.

### **Features & Functionality**
✅ **Data Import and Preprocessing**
- Reads [Monthly Monthly Mean Dataset](https://www.data.gov.in/resource/monthly-seasonal-and-annual-maximum-temperature-1901-2019)and cleans the dataset.
- Handles missing values and formats data types.
- Utilizing and understanding different types of graph for data analysis and visualization.

✅ **Exploratory Data Analysis (EDA)**
- Descriptive statistics.
- Data distribution visualizations.

✅ **Data Visualization**
- Uses **Matplotlib & Seaborn** to create meaningful visual representations.

### **Results**
- Key findings and observations based on the dataset.
- Graphical representation of trends and patterns.
</details>

---

## 📌 Contributing
Feel free to **fork** this repository and contribute by adding more insights, visualizations, or improvements!

## 📌 License
This project is licensed under the **MIT License**.

