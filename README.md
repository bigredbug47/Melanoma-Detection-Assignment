# Melanoma Detection Assignment
>The Melanoma Detection Assignment of Upgrad &amp; IIITB | Global Program in Machine Learning &amp; AI <br>
> Based on the data of the images of malignant and benign oncological diseases, which were formed from the <b>International Skin Imaging Collaboration (ISIC)</b>. 
<br> Propose the a multiclass classification model using a custom convolutional neural network in TensorFlow. Build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
<br>A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Dataset](#datasDet)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Contact](#contact)

## General Information

### <b>Business Understanding</b>

<p> Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.
</p>
 

<p>
The company is looking at solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
</p>
 

<hr>
<br>

### <b>Business Objectives</b>

<li>You are required to build a multiclass classification model using a custom convolutional neural network in TensorFlow.
<li> The model shoud be CNN based which can accurately detect melanoma.
</li>

<hr>
<br>

## Dataset
The dataset consists of <b>2357 images of malignant and benign oncological diseases</b>, which were formed from the International Skin Imaging Collaboration (ISIC). 
<br>All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:
- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

<hr>

## Conclusions
- Using the dataset, we successfully implemented the CNN based models. But the baseline model has encountered the overfitting problem, due to the limit of training samples and imbalanced classes.
- We also experiments with multiple methods such as data agumentation, drop out layer and solving imbalanced classes to get the best model.
- The model has the best accuracy:
    - Train Set: 0.7784
    - Validation Set: 0.8510
    - Test Set: 0.4237


## Technologies Used
- Python - Version 3.8.10 64-bit
- Pandas - Version 1.3.0
- Numpy - Version 1.21.0
- Seaborn - Version 0.12.1
- Matplotlib - Version 3.4.2
- Tensorflow - Version 2.13.0


## Contact
Created by [@bigredbug47] - feel free to contact me!
