# Melanoma Detection Assignment
Cancer encompasses over 200 different types, with melanoma being the deadliest form of skin cancer. The diagnostic process for melanoma typically begins with clinical screening, followed by dermoscopic analysis and histopathological examination. Early detection is crucial, as melanoma is highly curable in its initial stages.

The first step in diagnosing melanoma involves a visual examination of the affected skin area. Dermatologists capture dermatoscopic images of skin lesions using high-speed cameras, achieving an accuracy of 65–80% without additional technical assistance. When these dermatoscopic images are further analyzed by cancer specialists, the diagnostic accuracy increases to 75–84%.

This project aims to develop an automated classification system utilizing image processing techniques to classify skin cancer based on skin lesion images.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- A model needs to be built to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Steps Involved

- Data Loading
- Baseline Model Building
- Training the Model and testing the model
- Building an augmented model
- Training the augmented model and testing the model
- Countering Class Imbalance with augmentor
- Building the final model
- Training the final model and testing the model
- Verifying the model

## Conclusions
As the model's accuracy improves, its loss decreases. The final model achieves 87% accuracy with a loss of 0.3, showing it can predict lesion classes with high precision. Using data augmentation and addressing class imbalance significantly boosted the model's accuracy.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Google Colab
- tensorFlow v2.11.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Melanoma Skin Cancer from https://www.cancer.org/cancer/melanoma-skin-cancer/about/what-is-melanoma.html

Introduction to CNN from https://www.analyticsvidhya.com/blog/2021/05/convolutional-neural-networks-cnn/

## Contact
Created by [@rupali1013] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
