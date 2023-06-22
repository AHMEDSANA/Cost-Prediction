# Cost-Prediction
In this project, we will predict the cost required for a patient depending on his/her health conditions.

<p align="center">
  <img width="" height="" src="https://github.com/AHMEDSANA/Cost-Prediction/assets/73955220/8033de82-f423-4d24-9bfe-c8f87b2538bb">
</p>

### Cost prediction:
Cost prediction using neural networks is a machine learning technique that uses neural networks to estimate or forecast the cost of a specific task, project, or product based on available data. The neural network learns patterns and relationships from historical cost data and other relevant variables to make predictions about future costs.

Here are the steps involved in cost prediction using neural networks:

### Gather data:

This includes historical cost data and other relevant features or variables that may impact the cost.

We will be using already gathered data in this project.

### Prepare data:

This involves cleaning and preprocessing the data, such as handling missing values, scaling variables, and encoding categorical variables.

<p align="center">
  <img width="" height="" src="https://github.com/AHMEDSANA/Cost-Prediction/assets/73955220/e335ae00-d8c7-4e50-af20-e61d3dcb48ea">
</p>

We cleaned the missing values, scaled the values, and normalized our data as you can see from the picture above.

### Design model architecture:

This involves deciding on the number of layers, types of activation functions, and connections between neurons in the neural network.

<p align="center">
  <img width="280" height="360" src="https://github.com/AHMEDSANA/Cost-Prediction/assets/73955220/fb3d4c5b-2252-48f6-99e9-c597d6592335">
</p>

### Train model:

This involves splitting the data into training and validation sets, feeding the training data into the neural network, and adjusting the model's weights and biases to minimize the difference between predicted and actual costs.

### Evaluate model:

This involves assessing the performance of the trained model using evaluation metrics such as mean squared error (MSE), mean absolute error (MAE), or root mean squared error (RMSE) on the validation set.

After the training, we tested our model by giving it different inputs and the values we received were in range of the original or ground truth values. Meaning our model was generalized well is not overfitting or underfitting.

<p align="center">
  <img width="360" height="360" src="https://github.com/AHMEDSANA/Cost-Prediction/assets/73955220/4e675bbf-1d1e-4732-b7d0-e5db02c8f864">
</p>

<p align="center">
  <img width="" height="" src="https://github.com/AHMEDSANA/Cost-Prediction/assets/73955220/6c7ea904-d438-454b-a0b0-fb21ae6ee406">
</p>

### Deploy model:

This involves applying the trained model to new, unseen data to make cost predictions. The model can be integrated into an application or system to provide real-time cost estimates.

Neural networks can capture complex relationships between input variables and cost, making them suitable for cost prediction tasks. They can handle non-linear relationships and adapt to different types of data, such as numerical and categorical variables.

Here are some of the benefits of using neural networks for cost prediction:

- They can capture complex relationships between input variables and cost.
- They can handle non-linear relationships.
- They can adapt to different types of data.
- They can be trained on large datasets.
- Here are some of the challenges of using neural networks for cost prediction:
- They can be computationally expensive to train.
- They can be difficult to interpret.
- They can be sensitive to the quality of the data.
 
### How to Run the code:
- To run the code just copy the code from the Python notebook file or download the file and run the file.
- The dataset link is already declared in the Python notebook file so it will download automatically. 
