# CNN Assignment - Melanoma Detection
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)
* [Contacts](#contacts)


## General Information
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


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

## Conclusions
- Accuracy on training data has increased by using Augmentor library
- Model is still overfitting
- The problem of overfitting can be solved by add more layer,neurons or adding dropout layers.
- The Model can be further improved by tuning the hyperparameter


## Technologies Used
Data loading and manipulation libraries
- pandas : Version - 2.0.3
- numpy : Version - 1.24.3

Data visualization libraries
- matplotlib.pyplot : Version - 3.7.2

CNN Library
- Tensor Flow : Version - 2.15.0
- Tensor Flow backed keras

Utility
- pathlib
- os
- PIL
- glob
- warnings


## Acknowledgements
This assignment was while doing MS in Artificial Intelligence and Machine Learning from IIIT Bangalore


## Contact
Created by [Bibhuti Ranjan Sinha](https://www.linkedin.com/in/bibhutiranjansinha/)  - feel free to contact me!