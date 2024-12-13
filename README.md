# **Uber Data Prediction**

This project, **Uber Data Prediction**, involves analyzing and predicting patterns in Uber trip data. The dataset includes features such as trip start and end dates, trip distance, purpose, and category. The goal is to perform exploratory data analysis, engineer relevant features, and build machine learning models to make predictions.

---

## **Key Features of the Project**

### **1. Data Exploration and Visualization**
- **Bar Plots**: Used to analyze trip frequency across categories and purposes.  
- **Count Plots**: Visualized the distribution of categorical features.  
- **Box Plots**: Analyzed the distribution of miles traveled for various trip purposes.

### **2. Feature Engineering**
- Extracted new features such as:
  - Trip duration from `start date` and `end date`.
  - Day of the week and hour of the day from `start date`.
  - Miles traveled as a numerical feature for modeling.
- Handled missing values and encoded categorical variables.

### **3. Predictive Modeling**
- Implemented machine learning models for predictions:
  - **Support Vector Regressor (SVR)**: For predicting continuous variables like miles or trip duration.
  - **Logistic Regression**: For classifying trip categories or purposes.

### **4. Model Evaluation**
- Evaluated model performance using:
  - **Mean Squared Error (MSE)**: Measures the average squared difference between predicted and actual values.
  - **Mean Absolute Error (MAE)**: Measures the average absolute difference between predicted and actual values.
  - **R2 Score**: Indicates the proportion of variance explained by the model.

---

## **Dataset Columns**
The dataset includes the following columns:  
1. **start_date**: Start timestamp of the trip.  
2. **end_date**: End timestamp of the trip.  
3. **category**: Type of trip (e.g., Business, Personal).  
4. **start**: Starting location of the trip.  
5. **stop**: Ending location of the trip.  
6. **miles**: Distance traveled during the trip.  
7. **purpose**: Purpose of the trip (e.g., Meeting, Commute).
