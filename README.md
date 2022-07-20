# Melanoma Detection via Convolutional Neural Network (CNN)

The objective of this project is to create a Convolutional Neural Network (CNN) to classify a dermoscopic image of a skin lesion as Melanoma or Non-Melanoma. A dermoscopic image is a picture of the skin using a microscope and illumination.

## Motivation

Melanoma is the deadliest and most aggressive form of skin cancer; it is projected that in 2018, Melanoma of the skin will cause 9,320 deaths in the United States. However, if Melanoma is caught in an early stage, the 5-year survival rate is about 99%. Therefore, the early detection of Melanoma, before metastasis, is critical for patient survival.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

## Built With

* TensorFlow
* Keras
* Python
* matplotlib

## Models

Three CNN architectures were explored for this project:

1) Simple CNN built from scratch with Keras, TensorFlow, and Python.
2) Added dropouts layers to overcome issue of overfitting.
3) Added augumented images to overcome class imbalance and applied batch normalization on final CNN model.

## Results
The CNN built in Keras is able to achieve an overall accuracy of 80% on Validation dataset. This is actually good for such a simple CNN and takes about 30 epochs to train While this CNN is simple and straightforward to understand, it does not yield the same level of accuracy as a deeper CNN with trasfer learning can acheive.