# Image Processing

## Problem Statement

### To classify human-eye images by disesase/normal using `Convolutional Neural Network`


## Data Dictionary


|Category|Description|
|---|---|
|Cataract|Human eye with Cataract|
|Glaucoma|Human eye with Glaucoma|
|Retinopathy|Human eye with Retinopathy|
|Normal|Normal Human eye|


## Summary
The work starts with importing the image data, each folder of images corresponding to a classification category is fetched and the images are processed. The image processing includes resizing of image and converting it into a numpy array which is then normalized. The `read_data()` returns features and its corresponding category. The input and output data are set.

Testing and training data are splitted. A Sequential model is created with a convolution2D layer, Maxpooling2D layer and Dense layer. The output layer has 4 nodes since we have 4 categories. The model is compiled and fitted. The performance of the model is then visualized.


## Conclusion
From the visualization it is observed that the accuracy of the model is slightly better with the training data in comparison with test data, but the overall accuracy is great. The loss of the model is observed to be less which shows better performance of the model.

