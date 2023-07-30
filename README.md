# Melanoma Detection - CNN based based assignment

Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Overall Approach](#overall-approach)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

This is a an assignment done as part of Executive PG Programme in Machine Learning & AI - January 2023, offered by IIIT - Bangalore in association with Upgrad.

Name: Bharat Hegde

Email: bharathhegde2005@gmail.com

30th July 2023

Bharat_Hegde_nn.ipynb : Contains the Python code used for building the model

README.md : This file which contains the general description of the project

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Overall Approach

Melanoma will use CNN models.

Following is the general apporach:

* Since the Tensorflow / GPUs are involved, we use Google Collab to create and run the model

* The Train data is hosted on my Google Drive. If you want to run the notebook for yourself, please change the data path. 

* Data preparation : We create the image datasets ( Training and Validation) using the uploaded data

* Model building and evaluation : We initially build a simpler CNN model. Then we see that the model overfits.  As next step, we try a simple data augmentation strategy, which fails poorly. Then we see that there is class imbalance, and we use augmentation to create additional images, which solve class imbalance. Then we create a final model and we see that overfit problem is solved.

The python language is used for all above steps. The libraries used as numpy, panda, matplotlib, seaborn, tensorflow


## Conclusions

Summarizing results.

The initial model that we built overfit due to class imbalance in the data. By solving the class imbalance, we see that the problem of overfitting is sufficiently solved.

Training accuracy: 0.9271 and validation accuracy: 0.8048

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 
- Tensorflow
- numpy
- panda
- matplotlib
- seaborn


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@bharathhegde] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->