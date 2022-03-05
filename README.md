# Project work for AIT Deep Learning Class


## Marcell Mesterházi

### Dermatological classification

#### My project is about to classificate the types of skin cancer. The first [dataset](https://challenge.isic-archive.com/data/) is from a Deep Learning challenge - ISIC Challenge 2018 - and it contains 10015 28x28 pixel large images (DermaMNIST.ipynb).

#### After a short consultation with Gyires-Tóth Bálint, my plan is to use [this](https://www.kaggle.com/c/siim-isic-melanoma-classification/) dataset as my **second and main** dataset (ISIC_Melanoma.ipynb). This code is runnable in Google Colab also.
##### I preprocessed the csv and the image files and splitted the dataset

#### If anything goes well, I want to draw a bounding box around the suspicious area and a probability value.

##### I'm also planning to implement this model in an Android application. The App would use the camera of the phone and the application draws a bounding box around the suspicious area and inform the user about it's own prediction.