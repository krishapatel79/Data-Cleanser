
# 🧹 Patient Health Data Cleanser
### Data Preprocessing & Feature Engineering Project

## 📌 Project Overview
This project focuses on data preprocessing and feature engineering for a healthcare dataset containing patient health records.
The dataset includes missing values and outliers, which must be handled before using the data for machine learning models.

The objective of this project is to apply different missing value imputation techniques and outlier detection methods
to create a clean and machine-learning ready dataset.

---

# 🎯 Objectives
- Perform data exploration and profiling
- Identify and analyze missing values
- Apply multiple imputation techniques
- Detect and handle outliers using statistical methods
- Compare data before and after cleaning
- Produce a final clean dataset ready for ML models

---

# 📂 Dataset Information

The dataset contains patient health records with the following features:

| Column | Description |
|------|------|
| patient_id | Unique identifier for each patient |
| age | Age of the patient |
| gender | Gender of the patient |
| region | Residential region |
| bmi | Body Mass Index |
| blood_pressure | Average systolic blood pressure |
| cholesterol | Cholesterol level |
| glucose | Fasting glucose level |
| disease_risk | Target variable (0 = Low Risk, 1 = High Risk) |

---

# 🔍 Missing Value Handling

The following imputation techniques were implemented:

### 1️⃣ Simple Imputer
- Mean imputation for numerical columns
- Most frequent value for categorical columns

### 2️⃣ Missing Indicator
Binary columns created to track missing values.

Example:
age_missing, bmi_missing, cholesterol_missing, glucose_missing

### 3️⃣ KNN Imputer
Uses K-Nearest Neighbors to estimate missing values based on similar data points.

### 4️⃣ MICE (Iterative Imputer)
Uses Multivariate Imputation by Chained Equations to predict missing values using other features.

---

# ⚠️ Outlier Detection & Treatment

Outliers were detected and handled using multiple statistical methods.

### 1️⃣ Z-Score Method
Detects extreme values based on standard deviation.

### 2️⃣ IQR Method
Uses Interquartile Range to detect unusual values.

### 3️⃣ Percentile Capping
Caps extreme values at 1st and 99th percentile.

### 4️⃣ Winsorization
Limits extreme values without removing rows.

---

# 📊 Data Visualization

The project includes multiple visualizations:

- Missing value heatmap
- Boxplots for outlier detection
- Before vs After comparison

Libraries used:
- Matplotlib
- Seaborn

---

# ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

---

# 📈 Results

After data cleaning:

✔ Missing values handled  
✔ Outliers treated using multiple statistical techniques  
✔ Dataset quality improved  
✔ Final dataset ready for machine learning models  

---

# 📁 Project Structure

Patient-Health-Data-Cleanser
│
├── data_cleanser_complete_project.ipynb
├── patient_health_dataset.csv
├── clean_patient_dataset.csv
└── README.md

---

# 🚀 How to Run the Project

1️⃣ Clone the repository

git clone https://github.com/your-username/patient-health-data-cleanser.git

2️⃣ Install required libraries

pip install pandas numpy scikit-learn matplotlib seaborn scipy

3️⃣ Run the notebook

Open Jupyter Notebook and run:
data_cleanser_complete_project.ipynb

---

# 🎥 Project Explanation Video

You can watch the complete project explanation here:

🔗  https://drive.google.com/file/d/1NwqjlkFGoEi4u39SSW2q7Rvi25ycneIt/view?usp=sharing

---