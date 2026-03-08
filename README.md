# Customer Churn Prediction using Artificial Neural Network

## Project Overview
This project focuses on predicting customer churn using an Artificial Neural Network (ANN). Customer churn refers to the situation where customers stop using a company's services. Predicting churn helps businesses identify customers who are likely to leave and take steps to retain them.

In this project, a neural network model is trained on customer data from a bank to predict whether a customer will exit the bank or continue using its services.

---

## Dataset
The dataset contains customer information such as:

- Credit Score  
- Geography  
- Gender  
- Age  
- Tenure  
- Balance  
- Number of Products  
- Has Credit Card  
- Is Active Member  
- Estimated Salary  

The target variable is **Exited**, where:
- **0** represents a customer who stayed with the bank
- **1** represents a customer who left the bank

---

## Project Workflow

### Data Preprocessing
The dataset is first cleaned and prepared for training. Categorical features such as geography and gender are converted into numerical format so that they can be used by the neural network. The dataset is then split into training and testing sets. Feature scaling is also applied to ensure that all variables are on a similar scale.

### Model Building
An Artificial Neural Network is created with multiple fully connected layers. The hidden layers use ReLU activation functions, while the output layer uses a sigmoid activation function since the task is a binary classification problem.

### Training
The model is trained on the training dataset using mini-batch gradient descent. Early stopping is used during training to prevent overfitting by stopping the training process when the validation loss stops improving.

### Model Evaluation
After training, the model is evaluated using the test dataset. The performance of the model is analyzed using a confusion matrix and accuracy score to determine how well the model predicts customer churn.

---

## Technologies Used
- Python  
- TensorFlow / Keras  
- Pandas  
- NumPy  
- Scikit-learn  

---

## Key Concepts Demonstrated
- Data preprocessing  
- Feature encoding  
- Feature scaling  
- Artificial Neural Networks  
- Binary classification  
- Model evaluation  

---

## Future Improvements
Possible improvements to this project include hyperparameter tuning, adding dropout layers to reduce overfitting, experimenting with different neural network architectures, and comparing the ANN model with other machine learning algorithms.
