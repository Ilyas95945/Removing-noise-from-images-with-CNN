# Removing-noise-from-images-with-CNN

The aim of this project is to obtain clearer and higher quality images by reducing or eliminating unwanted noise in noisy images. This project aims to increase the usefulness of noisy images that can be used in various fields (e.g. medical imaging, photography, video processing). AI models use learned knowledge to reduce noise by recognizing patterns and structures in noisy images. This project focuses on improving noisy images to achieve better visual quality and more accurate analysis results.

![imageAı](https://github.com/Ilyas95945/Removing-noise-from-images-with-CNN/assets/129670343/cf56a751-365f-4250-88be-35c12df220df)

 # Model: CNN(Convolutional Neural Network)

 The CNN (Convolutional Neural Network) model used to remove noise in images has an architecture consisting of convolution layers and activation functions to produce clean images from noisy images. In the model where noisy images are given as input, features are extracted from the image with convolution layers and these features are processed using activation functions such as ReLU. The output layer recreates the clean image. The model is trained using loss functions such as Mean Square Error (MSE) or Structural Similarity Index (SSIM) on pairs of noisy and clean images and is optimized with optimization algorithms such as Adam. During the training process, the generalization ability of the model is increased with data augmentation techniques.

Training loss indicates how inaccurate the predictions the model makes on the training data set are. During the training process, the model's parameters are adjusted to minimize errors on the training data. Training loss generally decreases over the course of training because the model adapts better to the training data. Low training loss indicates that the model has learned the training data well. However, a very low value may mean that the model may have lost its ability to generalize by overfitting the training data.

Validation loss indicates how inaccurate the predictions the model makes on the validation data set are. This data set is used to monitor the performance of the model during training and the model is not trained with this data. Validation loss usually decreases for a period of time, then may remain constant or begin to increase. Low validation loss indicates that the model adapts well to new data beyond the training data. High validation loss may indicate that the model is overfitting to the training data and has poor generalization ability. 

![indir](https://github.com/Ilyas95945/Removing-noise-from-images-with-CNN/assets/129670343/f50d4250-13ed-42c6-8de6-8d8ccb8b54ba)

Interpretation of Charts
The fact that the training and validation losses are both low and close to each other indicates that the model adapts well to both the training data and the new data. If the training loss is low but the validation loss is high, the model has overfitted the training data and cannot generalize to new data. If both training and validation losses are high, it means that the model has not learned both the training data and the new data well.

These graphs are used to monitor the model's behavior during the training process and make necessary adjustments. Tracking validation loss is critical, especially to prevent overfitting situations.


![indir (1)](https://github.com/Ilyas95945/Removing-noise-from-images-with-CNN/assets/129670343/2dd0b037-fef1-4049-b1e1-75f9bf965de4)

Model accuracy: 97.18%


