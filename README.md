# Melanoma Detection
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC).
- What is the background of your project?
The dataset contains images of 9 different cancers. This project is about creating a neural network model to detect Melanoma Cancer images from other cancer images.
- What is the business problem that your project is trying to solve?
To build a CNN based model which can accurately detect melanoma.
- What is the dataset that is being used?
The dataset consists of 2357 images of malignant and benign oncological diseases

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Model 1 - CNN Multi layers with dropouts  - This one resulted in under-fit. No good accuracy for train data. model performed similar for both "train dataset" and "Validation dataset"
- Model 2 - CNN layers with image augmentation - Data augmentation was added to balance the data, looks like adding extra layers and batch normalisation is not helping much.
- Model 3 - CNN Layers - reduced complexity - reducing the layers, normalisation and dropouts, Accuracy improved, simple model saves the day.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Google Collab
- library - pandas, numpy, matplotlib, tensorflow, keras, sklearn
- Augmentor
- Dataset
##Ref:https://towardsdatascience.com/downloading-datasets-into-google-drive-via-google-colab-bcb1b30b0166
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@srikanthsuryawanshi] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
