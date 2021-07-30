# Gender-Age-Predictor
Code to demonstrate the prediction of Age and gender by inputing a image through openCV library.
# DATASET USED : 
https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/

## It covers the following points:
* Read the downloaded Caffe Model file as Training for Age and gender prediction.
* Converting image from BGR to RGB .
* Here, we only need to focus on the just facial area of the image. Luckily, openCV provides a face detector. So, we use the face detector.
* And at last, our model predict the age and gender for the provided image.

## To run the code:
1. Clone the github repository in your computer. ```git clone https://github.com/AmolAgarwal12/Gender-And-Age-Prediction-Project.git```
2. Run ```age_and_gender.ipynb``` file which can be run on any environment like Jupyter Notebook, Google colab etc. It is training file.
3. Testing file : ```Testing.ipynb```
4. That's it.
