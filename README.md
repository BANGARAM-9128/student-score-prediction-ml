# Student Performance Prediction using Linear Regression

## Project Overview

This project uses **Simple Linear Regression** to predict a student's **Overall Score** based on the number of **Study Hours**. The objective is to analyze the relationship between study time and academic performance and build a machine learning model capable of estimating student scores.

---

## Dataset

The dataset contains information related to student academic performance, including:

* Age
* Study Hours
* Attendance Percentage
* Math Score
* Science Score
* English Score
* Overall Score
* Final Grade

### Data Preprocessing

The following preprocessing steps were performed:

1. Loaded the dataset using Pandas.
2. Checked dataset structure and summary statistics.
3. Verified the presence of missing values.
4. Removed duplicate records.
5. Dropped unnecessary columns:

   * `student_id`
   * `internet_access`
   * `extra_activities`
6. Converted categorical grades into numerical values for analysis.

---

## Exploratory Data Analysis (EDA)

A correlation analysis was performed to understand relationships between numerical features.

### Correlation Heatmap

A heatmap was generated using Matplotlib to visualize feature correlations.

Key observation:

* **Study Hours** showed a strong positive correlation with **Overall Score**.
* Therefore, `study_hours` was selected as the independent variable for the regression model.

---

## Machine Learning Model

### Algorithm Used

* Simple Linear Regression
* Library: Scikit-Learn

### Feature and Target

**Feature (X):**

* Study Hours

**Target (y):**

* Overall Score

### Train-Test Split

* Training Data: 80%
* Testing Data: 20%
* Random State: 42

---

## Model Evaluation

The model was evaluated using:

* R² Score
* Mean Squared Error (MSE)

These metrics help measure how well the model predicts student performance.

---

## Prediction Example

The trained model can predict a student's overall score based on study hours.

Example:

* Input: Study Hours = 2
* Output: Predicted Overall Score

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Jupyter Notebook

---

## Project Structure

```text
├── linearregression.ipynb
├── Student_Performance.csv
├── README.md
```

---

## Results

The analysis demonstrates that study hours have a significant impact on student overall performance. The linear regression model successfully captures this relationship and can be used to estimate student scores based on study habits.

---

## Future Improvements

* Multiple Linear Regression using additional features
* Feature engineering
* Outlier detection
* Hyperparameter optimization
* Interactive visualization dashboards
* Model deployment using Flask or Streamlit

---

## Author

Machine Learning Project – Student Performance Prediction using Linear Regression.
Name: GRANDHI RAJA SEKHAR
Email: grandhirajsekhar8211@gmail.com
Linkedin: https://www.linkedin.com/in/grandhi-raja-sekhar-2553a2305/