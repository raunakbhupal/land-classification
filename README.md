# Land Cover Segmentation and Classification
This repository outlines a project conducted as part of the CS-GY 6953 Deep Learning course during the Spring 2023 semester. The project focuses on image segmentation and classification, showcasing the coursework's practical application in the field of deep learning.

## Prerequisites
Python 3.8+

## Dataset
The dataset we used is taken from the DeepGlobe Challenge of Land Cover Segmentation in 2018. [[DeepGlobeChallenges]](http://deepglobe.org/challenge.html). While the original dataset has been removed from the source, we obtained it from Kaggle. The data, along with comprehensive information and labels, is available at [[Kaggle Link]](https://www.kaggle.com/datasets/balraj98/deepglobe-land-cover-classification-dataset?resource=download) However, please note that the validation and test images do not have corresponding masks in this dataset.

To address this, we incorporated an alternative dataset where the training data was split into both training and testing subsets. This additional dataset can be downloaded from the following [[Link]](https://www.kaggle.com/datasets/geoap96/deepglobe2018-landcover-segmentation-traindataset).

## Notebook Explanations

final_project.ipynb - this file contains the entire code for our project.

To run this file, open this on Google Colab, make sure the required dataset is uploaded and then run all the cells on GPU with High-RAM for results.
