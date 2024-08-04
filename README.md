# Deep-Learning_Breast-Cancer-Classification
## Description:
Breast cancer is the most common cancer amongst women in the world. It accounts for 25% of all cancer cases, and affected over 2.1 Million people in 2015 alone. It starts when cells in the breast begin to grow out of control. These cells usually form tumors that can be seen via X-ray or felt as lumps in the breast area.

The key challenges against it’s detection is how to classify tumors into malignant (cancerous) or benign(non cancerous). Classification model is developed using Neural Network and the Breast Cancer Wisconsin (Diagnostic) Dataset.

## Model Architecture:
The neural network model used in this project was built using TensorFlow and Keras. The architecture consists of the following layers:

* Input Layer:
'Flatten(input_shape=(30,))' - Flattens the input data of shape (30,) into a 1D array.
* Hidden Layer:
'Dense(20, activation='relu')' - Fully connected layer with 20 neurons and ReLU activation function.
* Output Layer:
'Dense(2, activation='sigmoid')' - Fully connected layer with 2 neurons and sigmoid activation function.

## Training the Model:

The model was compiled and trained using the following setup:

* Optimizer: 'adam'
* Loss Function: 'sparse_categorical_crossentropy'
* Metrics: 'accuracy'

The model was trained for 10 epochs with a validation split of 0.1.


## Objective:

1. Understand the Dataset & cleanup.

2. Build classification models to predict whether the cancer type is Malignant or Benign.

3. Also fine-tune the hyperparameters & compare the evaluation metrics of various classification algorithms.
