# Title : Robust Segmentation using Deep Learning

## Problem Statement: 
<b>Sematic Segmentation for Autonomous Vehicles. Self-driving cars is one up of the most advanced use-case of Computer Vision and Deep Learning in real-life. The vehicle needs to take input field in real-time and take instant and accurate decisions.
A small error or even a fraction of a second elapsed extra would lead to disastrous results. For building accurate systems, the system should focus on the important parts of image instead of running the analysing algorithms on the entire image.
To enhance this field of extracting important parts of the image, various segmentation techniques are used. These algorithms play a crucial part in the development and training of such vehicles as lots of human lives are at stake.
</b>

## Methodology:
To witness all the phases of development of autonomous vehicles, we started off with some Naïve Algorithms like threshold segmentation, edge detection segmentation and clustering using K-means Machine Learning Algorithm.
A deployed solution for the above is given in the “Intermediate Results section”.
These enhance the input to the model for making enhanced predictions. The main focus is to maximize ROI(region of interest), that algorithms like UNet, EfficientNet, FPN, Mask RCNN etc do efficiently and produce satisfactory results.

## Results - Version-1:
<b>Image Segmentation using K-Means Clustering </b> <br>

  repo link : https://github.com/vineethm1627/kmeans_segmentation <br>
  Deployed Website (version-1) : http://imgsegkmeans.herokuapp.com/ <br>
    Steps to play around with the application : <br>
  - In the main page, upload the input picture
  - In the sidebar on the left, you can alter the hyperparameter "K" to observe different results.
  - Each time the value of k is altered, the screen refreshes itself to load the updated results.
  
## Results - Version-2:
<b>Semantic Image Segmentation</b> <br>
deeplabv3+ model trained on pascal voc dataset for Semantic Image Segmentation using PixelLib <br>

  repo link : https://github.com/vineethm1627/semantic_segmentation
  
## Results - Version-3:
<b>Instance Image Segmentation</b> <br>
Mask R-CNN model trained on coco dataset for Instance Segmentation using PixelLib

  repo link : https://github.com/vineethm1627/instance_segmentation

