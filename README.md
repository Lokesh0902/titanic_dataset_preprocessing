# titanic_dataset_preprocessing
# Titanic Dataset - Data Preprocessing & Analysis

This repository contains the implementation for a Titanic dataset preprocessing task, covering key steps in preparing data for machine learning. The goal is to clean, transform, and analyze the dataset in a way that improves its usability for predictive modeling.

## ✅ Task Objectives

### 1. Import the Dataset and Explore Basic Info
- Loaded the dataset using `pandas`.
- Explored data structure using `.info()` and `.describe()`.
- Identified column data types and missing values.

### 2. Handle Missing Values
- Missing numerical values were filled using **mean** or **median**.
- For categorical features, mode or a default value was used.

### 3. Encode Categorical Features
- Used **Label Encoding** or **One-Hot Encoding** to convert string labels into numeric form.
- Ensured no dummy variable trap by dropping one column if necessary.

### 4. Normalize/Standardize Numerical Features
- Applied **StandardScaler** or **MinMaxScaler** from `sklearn` to scale numeric columns.
- Ensures model training is not biased by feature magnitude.

### 5. Visualize and Remove Outliers
- Used **boxplots** from `seaborn` to identify outliers.
- Outliers were removed using Interquartile Range (IQR) method for cleaner data.

## 📊 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn`


