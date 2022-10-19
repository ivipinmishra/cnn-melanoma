# CNN Model
> This assignment is a multiclass classification model using a custom convolutional neural network in TensorFlow. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

- The data set contains the following diseases:

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
### Model 1
The accuracy of the model for the Training data set is at 95%. But the Validation accuracy is not in par with the training accuracy. It is only at 50%. The validation loss as observed is very high. This could also be indicative of some Overfit in the model. We could add some Dropout layers to improve the accuracy.

### Model 2
By using dropouts, model accuracy for Train data set has dropped to nearly 65%. The accuracy for the Validation set is at 55%. This is a much better model compared to the previous model as there seems to be No Overfit with the training accuracy 65% and validation accuracy at 55%.

### Model 3
#### Using Data Augmentation
 - Data Augmentation is primarily used for two reasons — to improve the variability of the dataset and also to increase the size of the dataset. This helps increase the robustness of the Deep Learning algorithm that is trained from this data.
 -The training accuracy seems to be nearly 95% and the validation accuracy is nearly 80%. Though the model accuracy has improved, the class rebalance has helped treat the overfitting to some extent.
- The class rebalance has helped treat the overfitting to some extent.
## Technologies Used
- matplotlib
- pandas
- numpy
- seaborn
- sklearn
- keras


## Acknowledgements
Give credit here.
- This project was inspired by Upgrad AI-ML Journey.
- Reference: https://upgrad.com/
- This project was based on [Upgrad AI-ML CNN Module](https://upgrad.com).


## Contact
Created by [@v181080] - feel free to contact me!
