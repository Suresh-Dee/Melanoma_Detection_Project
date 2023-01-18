Project Name: Melanoma Detection Project

Problem Statement:
    To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma and the solution has potential to reduce a lot of manual effort needed in diagnosis.

Scope of Analysis:
    The goal of the project is to build a CNN based model which can evaluate images and alert the dermatologists about the presence of melanoma. Considering the input data provided, the CNN model is to take into account underfitting/overfitting, class imbalance and data augmentation strategy and hyperparameters tuning.

Approach:
    Data understanding
    Data creation
    Data visualization
    Model building & training
    Data augmentation
    Model building & training on augmented data
    Handling class imbalances
    Model building & training on the rectified class imbalance data

Source of Data:
    Data are provided in the folder "Skin cancer ISIC The International Skin Imaging Collaboration" which contains train and test images. The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC. All images were sorted according to the classification taken with ISIC. The data set contains the following diseases:
    Actinic keratosis, Basal cell carcinoma,Dermatofibroma, Melanoma, Nevus, Pigmented benign keratosis, Seborrheic keratosis, Squamous cell carcinoma, Vascular lesion

Conculsion/Inference:
    First model: 
    The training and validation accuracies were poor with the first model. Tt was concluded that the model was not fitting well with the data (underfitting) and it could be due to imbalance in the data.
    Second model:
    In the second model, variants of images were added with the original train data set using ImageDataGenerator and model was built considering different model architecture. There was no significant improvement in the prediction
    Third model:
    In the third model, data augmentaion was done to increase image quantity to 500 in each disease categories. The model was built with different model architecture including batch normalization. Accuracy was improved significantly in both training and validation. However, validation accuracy was less noticeably and it could be due to overfitting.
    Fourth model:
    In the fourth model, third model architecure was retained except removal of batch normalization. This resulted in better model without overfitting issue. This model was considered as final model to predict test data.

CNN Model:
    CNN Model is built considering suitable layers, optimizer, data augmentation and other techniques to predict the images correctly with high accuracy.

Technologies used:
    Tensorflow, Keras, Numpy, Pandas, matplotlib.pyplot

Acknowledgemnts
    The project was assigned and guided by Upgrad

Contact
    Created by Suresh

