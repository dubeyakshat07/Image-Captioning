# Image-Captioning

# tensorflow-gpu has been used.

# My computer specifications:
core i5-7200u, Nvidia 940MX(2GB), 8 Gigabytes of RAM

1. We have used FLickr8k_Dataset for training and testing our model which contains 8000 different images with 5 captions per image.

2. We need to convert every image into a fixed sized vector which can then be fed as input to the neural network. For this purpose, we opt for transfer learning by using the InceptionV3 model (Convolutional Neural Network) created by Google Research.
This model was trained on Imagenet dataset to perform image classification on 1000 different classes of images.

3. For Word Embeddings pre-trained GLOVE model has been used. 

4. We have used RNN-LSTM neural network.

# References:
https://towardsdatascience.com/image-captioning-with-keras-teaching-computers-to-describe-pictures-c88a46a311b8?

https://github.com/hlamba28/Automatic-Image-Captioning
