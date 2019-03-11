# Udacity_Traffic_light_classifier

---

In this project, we will use computer vision techniques to build a classifier for images of traffic lights! From a given dataset of traffic light images in which one of three lights is illuminated: red, yellow, or green.

In this notebook, we wil pre-process these images, extract features that will help us distinguish the different types of images, and use those features to classify the traffic light images into three classes: red, yellow, or green. The tasks will be broken down into a few sections:

1. **Loading and visualizing the data**. 
      The first step in any classification task is to be familiar with data; we will need to load in the images of traffic lights and visualize them!

2. **Pre-processing**. 
    The input images and output labels need to be standardized. This way, we can analyze all the input images using the same classification pipeline, and we know what output to expect when we eventually classify a *new* image.
    
3. **Feature extraction**. 
    Next, we'll extract some features from each image that will help distinguish and eventually classify these images.
   
4. **Classification and visualizing error**. 
    Final function will use our features to classify *any* traffic light image. This function will take in an image and output a label. Given code will help to  determine the accuracy of our classification model.    
    
5. **Evaluate your model**.
    Our classifier accuracy is  >95% a and will never classify any red lights as green
    
Here are some sample images from the dataset (from left to right: red, green, and yellow traffic lights):
<img src="images/all_lights.png" width="50%" height="50%">
