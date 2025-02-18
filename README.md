# Data Analytics and Visualization

This repository contains scripts and datasets used for Data Analytics and Visualization assignments. Each assignment includes data processing, statistical analysis, and visualization tasks performed on different datasets.

---

## 📌 Assignments

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

📌 Dataset Links:
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
  <summary><strong>Assignment 2: Python-Based Data Analysis and Visualization</strong></summary>

### **Overview**
This repository contains the data analysis and visualization assignment completed by **Omni Manwani (202211060)**. The notebook provides insights using Python-based data processing and visualization tools.

### **Installation & Setup**
To run this project, you need Python and Jupyter Notebook installed. You can set up the required environment by following these steps:

#### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Python libraries

#### Installing Dependencies
To install all required libraries, run:
```bash
pip install pandas numpy matplotlib seaborn
```

### **Usage**
#### Running the Notebook
1. Clone this repository:
```bash
git clone <repo-url>
```
2. Navigate to the project folder:
```bash
cd <repo-folder>
```
3. Open Jupyter Notebook:
```bash
jupyter notebook
```
4. Open `DAV2.ipynb` and run the cells sequentially.

### **Data Analysis & Visualization Steps**
The notebook includes:
1. **Installing and Loading Necessary Libraries**
2. **Loading the Dataset**
3. **Data Cleaning and Preprocessing**
4. **Exploratory Data Analysis (EDA)**
5. **Visualizations using Matplotlib and Seaborn**
6. **Conclusions and Insights**

### **Results**
- Key findings and observations based on the dataset.
- Graphical representation of trends and patterns.
</details>

---

## 📌 Contributing
Feel free to **fork** this repository and contribute by adding more insights, visualizations, or improvements!

## 📌 License
This project is licensed under the **MIT License**.

