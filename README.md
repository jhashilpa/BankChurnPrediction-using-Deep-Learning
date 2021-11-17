# BankChurnPrediction-using-Deep-Learning
The aim of the project  is to create a Classification model to predict if the customer will leave the bank in some time.
The case study is from an open-source dataset from Kaggle.The dataset contains 10,000 sample points with 14 distinct features such as CustomerId, CreditScore, Geography, Gender, Age, Tenure, Balance etc. Link to the Kaggle project site:https://www.kaggle.com/mathchi/churn-for-bank-customers

1>Performed Data cleaning and Data preprocessing Steps.

2>SPlited the dataset into Training and Validation and created batches for both of them as we are going to Batch Gradient descent to train the modle.

3>Created two layered ANN( 1 hidden layera and 1 utput laye). The input layer conatins 16 newuron ,the hidden layer contains 6 neurons and the ouput layer hs 1 neuron.

4>Used Relu as activation function in the Input Layer and the hiddlen layer. As its a classifictaion problem,We have used Sigmoid in the output layer as the activation function.

5>Modle is trained and  average loss is being captures at each epoch.

6>Also implemented Batch Normalization and drop out layer to increase the accuracy.
