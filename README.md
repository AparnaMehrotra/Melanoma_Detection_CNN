# Skin Cancer Classification using Custom CNN Model
> To build a CNN based model which can accurately detect Melanoma and classify other skin conditions of 9 types including Melanoma 
> Melanoma accounts for 75% of skin cancer deaths. A solution that can evaluate images
> and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- The CNN model works to accurately classify the images into 9 skin cancer diseases. 
- Using CNN to classify 9 different skin cancer diseases. This will certainly reduce manual effort and prioritize treatment as timely detection of these diseases is the key.
- ISIC has provided 2239 sample images for all 9 kind of skin cancer diseases
- 9 different skin cancer diseases are : Actinic keratosis, Basal cell carcinoma, Dermatofibroma, Melanoma, Nevus, Pigmented benign keratosis, Seborrheic keratosis, Squamous cell carcinoma and Vascular lesion


## Conclusions
- Provided data shows class imbalance. 
- seborrheic keratosis shows minimum number of samples and pigmented benign keratosis have higher number of samples
- Augmentation strategy applied for balancing the class imbalance and reducing overfitting, underfitting issues
- Dropout layers are included to reduce overfitting.
- Images are normalized between 0-1 and resized 180*180
- The Final model gives around 86% training accuracy and 82% validation accuracy after 30 epochs

## Technologies Used
- Pandas - version 1.3.5
- Numpy - version 1.21.6
- tensorflow - version 2.8.2
- keras - version 2.8.0
- matplotlib - version 3.2.2
- seaborn - version 0.11.1
- Augmentor - version 0.2.10


## Acknowledgements
- This project was based on CNN model to classify skin cancer diseases accurately and is done as a part of Deep Learning module for the Executive PG Programme in Machine Learning & AI - IIIT,Bangalore.


## Contributors
- <a href="https://github.com/AparnaMehrotra/">Aparna Mehrotra</a>


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->


