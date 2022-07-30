# Neural-Networks
As an atrificial intelligence course project, we designed, analyzed and put to work a self-implemented neural network.

## Design phase
* We implemented different loss functions and their derivatives: Relu, Leaky Relu, Identical, Tangeant-hyperbolic, Sigmoid and Softmax
* We chose softmax as our cross-entropy function which will be applied on the output layer
![image](https://user-images.githubusercontent.com/41966479/181925495-7effa1ae-f254-4d3f-99a1-756dbcab0a13.png)
* Foreach layer, we implemented backward propogation algorithm to update the weights
* we enabled different initial weight assignments, normal and uniform
* At last, train, test and batching features have been added.

## Dataset
* The dataset consists of persian digits
  ![image](https://user-images.githubusercontent.com/41966479/181925591-9f198f90-fe58-44b5-80c8-2873659f0523.png)
* Below, you can observe the distribution of the dataset
  ![image](https://user-images.githubusercontent.com/41966479/181925610-467ca235-2d4f-4598-b603-6a69a6dd15c6.png)
* We split the data to 60-40% proportion for our train-test data preparation phase

## Analysis
* We modified these parameters for their effect on the network:
  - Initial weight distribution
  - Batch size
  - Learning rate
  - Activation functions
  - Epochs
* Also, we utilized regulariztion, momentum and overfitting-prevention methods to smooth our trained model

## Results
Epoch by epoch evaluative metrics' values have been displayed like the picture below. Overall accuracy was about 93% that was satisfying.
![ai-nn](https://user-images.githubusercontent.com/41966479/181925962-e378ee81-544e-45ac-b372-bef9dd6d1f23.png)
