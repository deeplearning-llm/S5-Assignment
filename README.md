# S5 Assignment
### Problem Statement
Building a CNN model to perform mutli-classification of MNIST dataset. It is a dataset of 60,000 small square 28×28 pixel grayscale images of
handwritten single digits between 0 and 9.

This Assignment has 4 files i.e,(model.py,utils.py,S5.ipynb,README.md)

1) The utils.py file contains the following functions:
    a) Data Preprocessing , Data Transformations
    b) CNN Training Functions
    c) CNN Test Functions 
    d) Evaluations
  
2) The model.py contains the Convolutional Neural Network Architecture which is trained on the MNIST images for Performing the classification Task 
   Below is CNN Architecture or the Model Summary :
  
   CONV2d--> CONV2d --> MaxPooling2d --> CONV2d--> CONV2d --> MaxPooling2d--> FC1 --> FC2 --> Log_softmax
   
   ![image](https://github.com/deeplearning-llm/S5-Assignment/assets/135349271/8f0d78a4-3f4c-40ba-9415-5890ef29a003)

3) S5.ipynb serves as the execution file where we import libraries to visulaize and plot the datasets and evaluate the model's performance.

### Model Metrics 

The Model is trained on images in batches, batch size being 512 and for 20 Epochs 
The following the Model Metrics 
![image](https://github.com/deeplearning-llm/S5-Assignment/assets/135349271/2b6ddaa5-f874-4795-97be-9407cf5d4a52)
Train set: Accuracy = 99.17%
Test  set: Accuracy = 99.26%

![image](https://github.com/deeplearning-llm/S5-Assignment/assets/135349271/e0d5329d-7ce7-40f9-9c3e-e94214923ed0)

