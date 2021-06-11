# Churn_Modelling

In this project we are going to consider a Dataset of 10000 customers of a bank that contains following features:
- RowNumber
- CustomerId
- Surname
- CreditScore
- Geography
- Gender
- Age
- Tenure
- Balance
- NumOfProducts
- HasCrCard
- IsActiveMember
- EstimatedSalary
- Exited

We are going to use these features and we are going to build an Artificial Neural Network (ANN) and train in order to find out wether the customer is going to exit the bank or not.

The complete project is divided into four parts
## Part 1 Data Preprocessing
- Importing Libraries
- Importing Dataset
- Encoding Categorical Data
- Splitting the Dataset into Training Set and Test Set
- Applying Feature Scaling

## Part 2 Building the ANN
- Initiallizing the ANN
- Adding the input layer and the first hidden Layer
- Adding the Second hidden layer
- Adding the Output Layer

## Part 3 Training the ANN
- Compiling the ANN
- Training the ANN on the training Set

## Part 4 Making the Prediction and Evaluating the Model
- Predicting the result of a Single Observation
- Predicting the Test Result
- Making the confusion matrix

**Parameters used for Part 1 of the Problem**

Use the ANN model to predict if the customer with the following informations will leave the bank:
Geography: France
Credit Score: 600
Gender: Male
Age: 40 years old
Tenure: 3 years
Balance: $ 60000
Number of Products: 2
Does this customer have a credit card? Yes
Is this customer an Active Member: Yes
Estimated Salary: $ 50000
So, should we say goodbye to that customer?

Conclusion
The ANN model predicted the results with accuracy of 86.05% with 279 errors.
79 errors were of type-I
200 errors were of type-II
