# Gastrointestinal-Tract-Images-Multiclass-Classification-using-CNN

## Project Overview

This project leverages deep learning techniques to classify medical images.The project uses Python and TensorFlow/Keras for building and training the CNN model.The aim of this repository is identify and classify 8 different types of images of gastrointestinal tract medical dataset. With 80 epochs, a validation accuracy of 71%.

## Dataset:
The dataset used for this project contains the following classes:

1. Dyed and lifted polyps
2. Dyed resection margins
3. Esophagitis
4. Normal cecum
5. Normal pylorus
6. Normal z-line
7. Polyps
8. Ulcerative colitis

Each image has been preprocessed for training, validation, and testing.

![image](https://github.com/user-attachments/assets/c56e92a2-bca0-4bb3-93b7-d5ea775cccee)



## Results

The model achieved the following metrics:
1. Final Training Accuracy: 73%
2. Final Validation Accuracy: 71%
3. Final Training Loss: 0.75
4. Final Validation Loss: 0.80
Confusion matrices and classification reports are used to evaluate performance on the test set.


## TO DO
First of all download the dataset at (https://datasets.simula.no/kvasir/). For this code, the dataset "Kvasir Dataset v2" was used. Then create three separate folders (one for testing, another one for training and validation) with all the eigth classes inside all of them. Divide the total dataset in 80% for training, 10% for testing and 10% for validation
