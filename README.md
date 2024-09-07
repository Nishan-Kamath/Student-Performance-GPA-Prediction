---

# Student Performance GPA Prediction 📚🔍

## Project Overview 🚀

This project aims to predict the GPA of students based on various factors such as age, gender, parental education, study habits, and extracurricular activities. By leveraging machine learning, specifically linear regression, the model helps analyze and forecast academic performance.

## Dataset Description 📊

- **Student ID**: Unique identifier for each student.
- **Age**: Ranges from 15 to 18 years.
- **Gender**: 
  - 0: Male
  - 1: Female
- **Ethnicity**: 
  - 0: Caucasian
  - 1: African American
  - 2: Asian
  - 3: Other
- **Parental Education**: 
  - 0: None
  - 1: High School
  - 2: Some College
  - 3: Bachelor's
  - 4: Higher
- **Study Time Weekly**: Weekly study hours (0 to 20).
- **Absences**: Number of absences (0 to 30).
- **Tutoring**: 
  - 0: No
  - 1: Yes
- **Parental Support**: 
  - 0: None
  - 1: Low
  - 2: Moderate
  - 3: High
  - 4: Very High
- **Extracurricular**: 
  - 0: No
  - 1: Yes
- **Sports**: 
  - 0: No
  - 1: Yes
- **Music**: 
  - 0: No
  - 1: Yes
- **Volunteering**: 
  - 0: No
  - 1: Yes
- **GPA**: Grade Point Average (2.0 to 4.0).
- **Grade Class**: Classification based on GPA:
  - 0: 'A' (GPA >= 3.5)
  - 1: 'B' (3.0 <= GPA < 3.5)
  - 2: 'C' (2.5 <= GPA < 3.0)
  - 3: 'D' (2.0 <= GPA < 2.5)
  - 4: 'F' (GPA < 2.0)

## Key Features 🔑

- **Data Cleaning**: Removed unnecessary attributes for better analysis.
- **Model Training**: Used Linear Regression to predict GPA.
- **Performance Metrics**: 
  - Mean Squared Error (MSE): 0.0382
  - R-squared: 0.9552

## Visualizations 📈

- **Actual vs Predicted GPA**: Scatter plot comparing actual and predicted GPA values.

## Example Prediction 🎯

Predicting GPA for a new student with the following details:
- Age: 17
- Gender: Female
- Parental Education: High School
- Study Time Weekly: 1 hour
- Absences: 3
- Tutoring: Yes
- Parental Support: Moderate
- Extracurricular: No
- Sports: Yes
- Music: No
- Volunteering: 2.5

**Predicted GPA**: 2.94

## How to Use 📋

1. Clone the repository.
2. Ensure you have the required libraries installed.
3. Load the dataset and run the model to make predictions.

## Installation 🛠️

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

---
