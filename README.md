# **Decision Tree Regression - Truth or Bluff**  
This project demonstrates the use of **Decision Tree Regression** to predict whether a job candidate's salary request is a bluff or true based on their position. Despite the limitations of decision trees for small datasets, I explored this technique to understand its behaviour in this context.

## **🛠 Technologies Used**  
**Programming Language:** Python  
**Libraries:**  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

## **📊 Project Overview**  
- **Goal:** Predict if a candidate's salary request is a bluff or true based on their position using **Decision Tree Regression**.  
- **Dataset:** Contains data with the following features:  
  - Job Position  
  - Salary Requested  

## **🔑 Key Learnings**  
- **Understanding Decision Tree Regression:**  
  - **Decision Tree Regression** creates a tree structure where each node represents a decision rule, and each leaf node contains the predicted value.  
  - While this method works well with larger datasets, it tends to **overfit** with small datasets, leading to poor generalization.  

- **Data Preprocessing:**  
  - Categorical data (job positions) was encoded using **OneHotEncoder**.  
  - Features were scaled using **StandardScaler** to help improve model performance.  

- **Model Training:**  
  - Built and trained the **Decision Tree Regression** model using **Scikit-learn**.  
  - Experimented with different tree depths and hyperparameters to reduce overfitting.  

- **Visualization:**  
  - Plotted the regression tree and compared predictions against actual values using **Matplotlib**.  
  - Evaluated the model’s performance and noted how decision trees can struggle with small datasets.  

## **🚀 Results**  
- The **Decision Tree Regression** model performed poorly due to overfitting, demonstrating the limitations of decision trees for small datasets.  
- The model was not able to generalize well, leading to inaccurate predictions for salary claims.  
- Highlighted the importance of selecting the right algorithm for the data size and considering alternative models, such as linear regression or support vector regression, for small datasets.
