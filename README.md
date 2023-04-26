# `Melanoma Detection Using CNN`

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

## General Information
-To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

**Goal:** `Develop CNN based model which can accurately detect melanoma.`

## Steps
 1. Importing and understanding Data
 2. Data Preparation and Visualization 
 3. Building Model 1
 4. Fine Tuning -Building Model 2
 5. Fine Tuning - Building Model 3
 6. Conclusion

## Dataset
The dataset consists of `2357` images of malignant and benign oncological diseases, which were formed from the `International Skin Imaging Collaboration` (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:
+ Actinic keratosis
+ Basal cell carcinoma
+ Dermatofibroma
+ Melanoma
+ Nevus
+ Pigmented benign keratosis
+ Seborrheic keratosis
+ Squamous cell carcinoma
+ Vascular lesion

## Conclusions
1) The model overfitted initially.
2) Added `Drop Out` to improve model and overcome Overfit problem.
3) Removed `class imbalance` problem using Data Augmentation.

## Technologies Used
+ Pandas
+ Numpy
+ Matplotlib 
+ Tensorflow & Keras
+ Glob

## Acknowledgements
+ This project was done part of the `Executive PG Programme in Machine Learning & AI - MLC45 batch.`

Please find the contributor details below:
+ Name: Vamsi Krishna P
+ Email ID: vamshi.krishna.prime@gmail.com
+ Phone no: (+91) 9491392912
+ Batch: ML C45
