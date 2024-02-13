# Melanoma Detection Assignment
Multiclass classification model using a custom convolutional neural network in TensorFlow.
> #### Problem Statement:
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
<!--* [Acknowledgements](#acknowledgements)-->

<!-- You can include any other section that is pertinent to your problem -->

## General Information
To build a multi class classification model using CNN which can accurately detect melanoma.
## Steps
 1. Importing and understanding Data
 2. Data Preparation and Visualization 
 3. Building Model - 1
 4. Fine Tuning By using Data augmentation
 5. Building model - 2
 6. Conclusion

## Dataset
The dataset consists of `2357` images of malignant and benign oncological diseases, which were formed from the `International Skin Imaging Collaboration` (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following classes:
+ Actinic keratosis
+ Basal cell carcinoma
+ Dermatofibroma
+ Melanoma
+ Nevus
+ Pigmented benign keratosis
+ Seborrheic keratosis
+ Squamous cell carcinoma
+ Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

**Final Observations from our model:**
1. Initially the model overfitted
2. Used data augmentation techniques & also handled class imbalance as there were few classes of data which have very few samples
3. It solved the problem of overfitting

## Technologies Used
- Pandas
- Matplotlib
- TensorFlow & Keras
- Augmentor

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

<!--
## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).
-->

## Contact
Created by [@naga-shanmukha]
