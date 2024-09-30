# 🧠 Stroke Data Analysis and Visualization Using Python

This project explores the **Stroke Prediction Dataset** from [Kaggle]([https://www.kaggle.com/fedesoriano/stroke-prediction-dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)), focusing on key demographic and health-related factors that influence stroke occurrence. The analysis uses Python to create interactive and modern visualizations that highlight trends and patterns across different features such as age, gender, smoking status, and medical conditions like hypertension and heart disease.

## 📊 Dataset Overview

The dataset contains the following patient details:
- **Age**
- **Gender**
- **Hypertension**
- **Heart Disease**
- **Smoking Status**
- **BMI (Body Mass Index)**
- **Average Glucose Levels**

These attributes help identify key risk factors for stroke, allowing healthcare professionals to gain valuable insights and potentially improve prevention strategies.

## 🧑‍💻 Methodology

### Step 1: Data Exploration and Cleaning
The dataset was loaded and cleaned using `pandas`. Missing values, if any, were handled appropriately. The dataset was then split into two groups: patients who experienced a stroke and those who didn’t.

### Step 2: Visualization and Analysis
Using **Seaborn** and **Matplotlib**, various features were visualized to highlight trends between stroke and non-stroke patients. The visualizations include:
- **Age distribution** between stroke and non-stroke patients.
- **Smoking Status** differences.
- **Gender distribution** comparison.
- **Heart Disease**, **Hypertension**, and **Work Type** breakdown.

### Key Features Visualized:

1. **Age Distribution**:
   - The age distribution shows clear differences between stroke and non-stroke patients.
   
2. **Smoking Status**:
   - Horizontal bar plots show how smoking habits correlate with stroke incidence.

3. **Gender Breakdown**:
   - The data highlights gender-based trends in stroke occurrences.

4. **Heart Disease and Hypertension**:
   - Bar plots indicate the proportion of patients with heart disease and hypertension, emphasizing the higher stroke risk for those with these conditions.

5. **Work Type**:
   - Various work types (e.g., private, government job, self-employed) are analyzed to see how they influence stroke occurrences.

### Custom Styling:
- The visualizations use the **mako** color palette from **Seaborn** for a modern and visually appealing look.
- Background color is set to **light gray** (`#d3d3d3`) to ensure readability.
- Data labels in the bar charts are displayed in **white** for contrast against darker bars, using annotations for each bar.

## 🔍 Final Results

The visualizations provide a clear overview of the factors associated with stroke. Significant patterns were found in patients with heart disease and hypertension, as well as those in specific work environments. These insights will help inform the development of machine learning models aimed at predicting stroke risk.

## 🛠 Technologies Used

- **Python**: The core language used for the analysis and visualization.
- **Libraries**: 
  - `Pandas` for data manipulation.
  - `Seaborn` and `Matplotlib` for creating visualizations.
  - `Numpy` for numerical computations.

## 🚀 Future Work

This analysis is just the beginning. In the next steps, I will apply **machine learning models** (such as **Logistic Regression**, **Random Forest**, and **Gradient Boosting**) to predict stroke risk using the dataset.

Stay tuned for the upcoming model predictions!
