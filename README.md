# AI-ML-Lab
# 🧠 Alzheimer's Disease Image Preprocessing

A comprehensive data preprocessing project developed using **Google Colab** for preparing an Alzheimer's Disease image metadata dataset for machine learning applications. This project demonstrates essential preprocessing techniques including data inspection, missing value handling, duplicate removal, outlier treatment, feature scaling, correlation analysis, train-test splitting, and data visualization.

---

## 📖 Introduction

Data preprocessing is a fundamental step in the data science and machine learning pipeline. Real-world datasets often contain inconsistencies, missing values, duplicate entries, and other issues that can negatively impact model performance. Effective preprocessing ensures that the data is clean, consistent, and suitable for analysis and predictive modeling.

This project utilizes an **Alzheimer's Disease MRI image metadata dataset** and performs preprocessing using **Google Colab** with Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn. The preprocessing workflow prepares the dataset for future applications in medical image classification, computer vision, deep learning, transfer learning, and explainable artificial intelligence (XAI).

---

## ✨ Features

- Load and inspect the dataset using Pandas
- Display dataset information and descriptive statistics
- Identify rows, columns, data types, and missing values
- Explore data using first, last, and random records
- Detect and handle missing values using appropriate techniques
- Remove duplicate records
- Detect and remove outliers using the Interquartile Range (IQR) method
- Apply feature scaling using:
  - Min-Max Normalization
  - Standardization (Z-score Scaling)
- Perform feature selection through correlation analysis
- Generate correlation matrices and heatmaps
- Convert data types where necessary
- Clean inconsistent and noisy data
- Split the dataset into training and testing sets
- Visualize feature distributions before and after preprocessing
- Compare original and preprocessed data
- Export the cleaned dataset as a new CSV file
- Document each preprocessing step with explanations and outputs

---

## 📂 Dataset

The dataset contains metadata extracted from Alzheimer's Disease MRI brain images.

### Classes

- **Non_Demented** – Healthy individuals without Alzheimer's disease
- **Very_Mild_Demented** – Early stage of Alzheimer's disease
- **Mild_Demented** – Mild stage of Alzheimer's disease

### Sample Attributes

- Split
- Disease
- Filename
- Extension
- Width
- Height
- Channels
- Color Mode
- File Size (KB)
- File Size (MB)
- Full Path

---

## 🛠 Technologies Used

- Google Colab
- Python 3

### Python Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---


## ⚙️ Preprocessing Workflow

1. Load the dataset
2. Inspect dataset information
3. Explore dataset records
4. Handle missing values
5. Remove duplicate records
6. Handle outliers
7. Apply feature scaling
8. Perform correlation analysis
9. Generate heatmap
10. Convert data types
11. Clean inconsistent data
12. Split into training and testing datasets
13. Visualize distributions
14. Compare before and after preprocessing
15. Save the cleaned dataset

---

## 📊 Output

The final output generates:

- Cleaned dataset
- Missing value report
- Duplicate removal report
- Outlier handling results
- Feature-scaled dataset
- Correlation matrix
- Correlation heatmap
- Histograms before preprocessing
- Histograms after preprocessing
- Training and testing datasets

---

## 📚 Applications

This preprocessing workflow can be applied in:

- Machine Learning
- Data Science
- Medical Image Analysis
- Alzheimer's Disease Research
- Computer Vision
- Deep Learning
- Explainable AI (XAI)

