# Dog vs Cat Classification with Transfer Learning

This project demonstrates a deep learning approach to classify images of dogs and cats using the MobileNetV2 model with transfer learning. The project utilizes the TensorFlow and Keras libraries to build, train, and evaluate the model, and leverages Kaggle's Dog vs Cat dataset for training.

## Project Overview

The goal of this project is to classify images of dogs and cats accurately using a pre-trained model (MobileNetV2). The process involves:

1. **Data Import and Preparation**: 
   - The dataset is imported from Kaggle and split into train and test sets.

2. **Model Building**:
   - MobileNetV2, a lightweight convolutional neural network, is used as the base model.
   - The base model is fine-tuned by adding custom layers for binary classification (dog vs cat).
   - Transfer learning is utilized by freezing the layers of the pre-trained model to retain the learned features.

3. **Training and Evaluation**:
   - The model is trained using the prepared dataset with appropriate hyperparameters.
   - The performance is evaluated based on accuracy and loss, ensuring the model's effectiveness.

4. **Prediction**:
   - The trained model is used to predict whether an image contains a dog or a cat.
