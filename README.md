# Title : Parameter Optimization Using SVM
Dataset Used : <a href = "https://archive.ics.uci.edu/dataset/602/dry+bean+dataset">Dry Bean Dataset </a> <br>
Images of 13,611 grains of 7 different registered dry beans were taken with a high-resolution camera. A total of 16 features; 12 dimensions and 4 shape forms, were obtained from the grains.
## **1. Methodology**
1. ***Data Loading and Preprocessing:*** Load the dataset containing student academic data. Preprocess the data, including handling missing values and encoding categorical variables.
2. ***Feature Engineering and Scaling:***  Perform any necessary feature engineering. In this code, it involves scaling the features using StandardScaler.
3. ***Train-Test Split and Sampling:*** Split the dataset into training and testing sets. Create multiple samples for cross-validation purposes.    
4. ***SVM Model Tuning:*** Define a parameter grid for hyperparameter tuning. Use GridSearchCV to search for the best combination of hyperparameters (C, gamma, kernel) using cross-validation.      
5. ***Model Evaluation and Result Visualization:***      
Evaluate the model's performance on each sample using the best hyperparameters found during tuning.Store the results, including sample number, best accuracy, and corresponding hyperparameters, in a DataFrame. Print the DataFrame displaying the results of each sample.
6. ***Select Best Model and Plot Learning Curve:*** Select the best-performing model based on the highest accuracy.Plot the learning curve of the best model using the learning_curve function from scikit-learn. The learning curve shows the model's performance on both the training and cross-validation sets as a function of the number of training instances.
## **2. Output**
1. Table
   <br>
   <img src = "" />
2. Convergence Graph
   <br>
   <img src = "" />
## **Details**
Name - Bhavya Bhalla 
<br>
Roll Number - 102103345
<br>
Subgroup - 3CO12
