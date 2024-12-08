## BUILDING SINGLE PERCEPTRON NEURAL NETWORK MODEL FOR REGRESSION PROBLEM FROM SCRATCH (NO ACTIVATION FUNCTION)
### 1. This projects is developed to understand the fundamentals of mathematics that goes behind the Neural network model. It covers topics such as Forward Propagation,Gradient descent , Backward propagation , concepts of weights and biases etc.
### 2. The Neural network model built here consisits one one perceptron having on einput feature and one output.
### 3. This model aims at solving the Regression problem.
![image alt](https://github.com/Rahul24qwerty/Building-Neural-Network-with-Single-Perceptron-for-Regression-Model-from-Scratch/blob/1bd83dded3291df5f0ade66eb2e15052474f7a20/nn_model.PNG)
## Workflow defined
#### a) Kaggle dataset -  "tvmarketing.csv"  data is imported as dataframe (containing two columns)
#### b) first column is x values and second column is the y values.There are total of 200 training data.
#### c) All values are normalized using Z-score normalization.
#### d) Arbitraty random values are assigned to weight (w) and 0 to bias (b) in matrix form.
## FORWARD PROPAGATION
#### e) predicted value "y_hat" is calculated using the formula:
![image alt](https://github.com/Rahul24qwerty/Building-Neural-Network-with-Single-Perceptron-for-Regression-Model-from-Scratch/blob/49ee23e3adf6fe563b4e29564fd7ef4f87eb064e/for_1.PNG)
#### f) Cost function is computed with actual values (y) and the predicted value (y_hat) using formula:
![image alt](https://github.com/Rahul24qwerty/Building-Neural-Network-with-Single-Perceptron-for-Regression-Model-from-Scratch/blob/715f8b2931c14e8d056d240d3fdabd4701116d0d/loss.PNG)
## BACKWARD PROPAGATION
#### g) We are going to minimize the cost function by changing the weight and bias values using gradient descent method.
#### h) In order to do that, we first need to calculate the derivation of cost function w.r.t weight and bias which is given by the formula:
![image alt](https://github.com/Rahul24qwerty/Building-Neural-Network-with-Single-Perceptron-for-Regression-Model-from-Scratch/blob/715f8b2931c14e8d056d240d3fdabd4701116d0d/deri_w.PNG)
#### 
![image alt](https://github.com/Rahul24qwerty/Building-Neural-Network-with-Single-Perceptron-for-Regression-Model-from-Scratch/blob/715f8b2931c14e8d056d240d3fdabd4701116d0d/deri_b.PNG)
#### i) Now weight (w) and bias (b) are updated every time the iteration runs in a loop.Formula for updating the weight and bias is given as: (We have used a learning rate = 0.05)
![image alt]()

## DATA VISUALIZATION
#### j) Below is the scatter plot for the original dataset, Noralized dataset and best fit line for the dataset
![image alt]()




