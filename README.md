# Animal Recognition using VGG16

## Introduction
This project is a part of the Habib University's CS 351 Artificial Intelligence coursework. The goal of this project is to build a convolutional neural network (CNN) that can classify images of animals. The dataset used for this project is the [Animals-10 dataset](https://www.kaggle.com/alessiocorrado99/animals10) from Kaggle. The dataset contains 10 classes of animals with 1300 images per class. The classes are as follows:
* dog
* cat
* wild bird
* chicken
* sheep
* cow
* elephant
* bear
* spider
* squirrel

## Methodology
The methodology used for this project is as follows:
1. Data Preprocessing
2. Model Building
3. Model Training
4. Model Evaluation

### Data Preprocessing
The data preprocessing step involves the following steps:
1. Loading the dataset
2. Splitting the dataset into training and testing sets
3. Resizing the images to 224x224
4. Normalizing the images
5. One-hot encoding the labels

### Model Building
The model building step involves the following steps:
1. Loading the VGG16 model
2. Removing the last layer of the VGG16 model
3. Adding a new layer to the VGG16 model
4. Freezing the weights of the VGG16 model
5. Compiling the model

### Model Training
The model training step involves the following steps:
1. Training the model
2. Saving the model

### Model Evaluation
The model evaluation step involves the following steps:
1. Loading the model
2. Evaluating the model

## Results
The model achieved an accuracy of 92.5% on the testing set. 

## Acknowledgements
- [Animals-10 dataset](https://www.kaggle.com/alessiocorrado99/animals10)
- [VGG16 model](https://keras.io/api/applications/vgg/#vgg16-function)
- [Dr. Saleha Raza](https://habib.edu.pk/SSE/syeda-saleha/)

## Authors
- [Ali Asghar Chakera](https://github.com/aliasgharchakera/)
- [Abbas Haider](https://github.com/smabbasht)
- Umema Zehra