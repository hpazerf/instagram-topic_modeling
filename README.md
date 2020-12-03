# instagram-topic_modeling

* Used an Instagram Scraper to collected 500 images from the National Geographic instagram account and labeled each image using the Google Vision API. Afterwards, engagement with each image post was assocaited with the image by creating a metric using the number of likes and comments. Using the engagement metric, a model was created to predict the engagement of any image that National Geographic posted. Finally, using LDA topic modeling, the images were grouped together into smaller topics to help decide the types of images the National Geographic receives the most engagement.
* Created this project in a group with 5 people including myself
* Used Google Colab 

# Assignment Overview

* Used an Instragram Scraper to collect 500 images posted by National Geographic Account including information about the number of likes, the numbers of comments, the caption of the image, and the image url.
* Using Google Vision, each image was given a series of labels based on what is in the image.
* Created an Engagement metric using the number of likes and comments.
* Created a Logisitc Regression Model to predict the engagement of an image using both the labels and the captions
* Found the topics for the images using LDA topic modeling
