# Project Report: Predictive Modeling of Knee Osteoarthritis Severity Grading

Osteoarthritis is a degenerative joint disease that affects millions of people worldwide. Diagnosing the severity of knee osteoarthritis is critical for determining appropriate treatment. This project aims to develop a machine learning model to predict the severity of knee osteoarthritis from knee X-ray images using computer vision.

## Objectives
To preprocess and prepare knee X-ray images for machine learning.
To build and train a Convolutional Neural Network (CNN) to classify the severity of knee osteoarthritis.
To evaluate the performance of the model.

We used a dataset of knee X-ray images labeled with their respective osteoarthritis severity grades (0 to 3). The project utilized Python programming language and TensorFlow/Keras libraries for implementing the CNN.

## Data Preprocessing 
Images were loaded and resized to a uniform dimension of 150x150 pixels. Pixel values were normalized to the range [0, 1].
The dataset was split into training (70%), validation (15%), and test (15%) sets.

## Model Building 
A CNN model was built using the Keras library.
The model was trained using the Adam optimizer and sparse categorical cross-entropy as the loss function. It was trained for 10 epochs.
The model performance was evaluated on the test set.
The CNN model showed promising results in classifying the severity of knee osteoarthritis.
