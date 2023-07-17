# Brain Tumor Detection with VGG-16

This is a project to detect brain tumors using the VGG-16 deep learning model. The dataset used in this project is the Brain Tumor Dataset.

## Data Preparation

The first step is to prepare the data. This involves loading the data, splitting it into training, validation, and test sets, and performing data augmentation on the training set.

## Model Training

The next step is to train the model. This is done using the Keras deep learning library. The model is a VGG-16 model with a few modifications. The first modification is to freeze the weights of the first 15 layers of the model. This is done to prevent overfitting. The second modification is to add a dropout layer to the model. This is done to prevent overfitting. The third modification is to add a dense layer to the model with a single output neuron. This is done to predict the class of the image.

## Model Evaluation

The model is evaluated on the validation set and the test set. The results show that the model achieves an accuracy of 91.5% on the validation set and 87.5% on the test set.

## Conclusion

This project demonstrates how to use the VGG-16 deep learning model to detect brain tumors. The results show that the model is able to achieve good accuracy on the task of brain tumor detection.
