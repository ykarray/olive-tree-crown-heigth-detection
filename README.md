# olive-tree-crown-heigth-detection
The summer internship project is to detect olive tree crown height without using any reference point, using deep learning techniques.
We have explored two methods for training deep learning
models to estimate crown heights.
The first method involves training a model using 2D images. By providing a dataset of 2D
images captured from smart phone 
The second method entails generating 3D images from the 2D images and training a deep
learning model using these 3D representations. 
# First method : 2D image
the 2D image method, as the name implies, our input consisted of 2D images. The first
step involved augmenting these images to improve the overall dataset. Then, we performed
object detection and segmentation using two different methods to generate the input for the
ResNet model. This ResNet model played a crucial role in predicting crown heights based on
the input generated from the previous steps.
![alt text](https://github.com/ykarray/olive-tree-crown-heigth-detection/blob/main/2dmethod.png)
# Second method:3D image
![alt text](https://github.com/ykarray/olive-tree-crown-heigth-detection/blob/main/3Dimagemethod.png)


the PCT code is in this repository :
https://github.com/ykarray/PCT-point-cloud-transformer-regression- 
