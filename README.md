# Customer Churn Prediction
This project implements an Artificial Neural Network (ANN) to predict customer churn, i.e., whether a customer is likely to leave a service or stay. Churn prediction is crucial for businesses to retain customers, reduce costs, and increase revenue through targeted retention strategies.

## Problem Statement

Given a dataset containing customer information such as demographics, service usage, account details, and past behavior, the goal is to build a model that classifies customers into:

Churned (1): Customer is likely to leave the service

Not Churned (0): Customer is likely to stay

## Model Architecture

Input Layer: Receives numerical and encoded categorical features from customer data.

Hidden Layers: One or more fully connected dense layers with activation functions (e.g., ReLU), optimized using backpropagation.

Output Layer: A single neuron with a sigmoid activation function that outputs a probability score between 0 and 1 for churn classification.

## Key Steps
### Data Preprocessing:

Handle missing values

Encode categorical features (e.g., OneHotEncoding or LabelEncoding)

Scale numerical values using StandardScaler or MinMaxScaler

### Model Building:

Use Keras  to define the ANN model

Compile using binary cross-entropy loss and an optimizer like Adam

### Training and Evaluation:

Train on the training set

Validate on a separate validation/test set

Evaluate performance using metrics like accuracy

### Prediction:

Use the trained model to predict churn probability for new/unseen customer data.

### Use Cases
Telecom, banking, SaaS platforms, and subscription-based businesses

Helps in proactive retention campaigns, personalized offers, and resource allocation
