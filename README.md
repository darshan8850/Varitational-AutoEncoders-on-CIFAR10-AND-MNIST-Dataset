# Varitational-AutoEncoders-on-CIFAR10-AND-MNIST-Dataset

This project aims to implement and train a Variational Autoencoder (VAE) on the CIFAR10 and MNIST dataset. VAEs are a type of generative model that can be used to generate new images by learning a compact, low-dimensional representation of the data.

## Dependencies
  * Python 3.x
  * Tensorflow 2.x
  * Numpy
  * Matplotlib
  * tqdm
  * Any other library as per requirement
  
## Data
The CIFAR10 dataset contains 60,000 32x32 color images in 10 classes, with 6,000 images per class. There are 50,000 training images and 10,000 test images. The MNIST dataset contains 60,000 28x28 grayscale images of handwritten digits, with 10 classes (0-9), with 6,000 images per class. There are 50,000 training images and 10,000 test images.

## Model
The model used in this project is a Variational Autoencoder (VAE) which is trained on the CIFAR10 and MNIST dataset. The VAE is a generative model that can be used to generate new images by learning a compact, low-dimensional representation of the data. The VAE consists of two main components: an encoder network that maps the input data to a low-dimensional latent space, and a decoder network that maps the latent space back to the original data space.

## Evaluation
The model's performance is evaluated by comparing the generated images with the original images. The evaluation metrics used to compare the generated images and original images are Mean Squared Error (MSE) and Structural Similarity Index (SSIM). 
Additionally, we also visualized the Latent space by using t-SNE plots. It helps to understand the how the model has learned the underlying structure of the data and how different classes are separated in the latent space, which allows us to check whether the model has learned to separate the different classes in the Latent Space.

## Installation
 1. Clone the repository
     git clone https://github.com/darshan8850/Varitational-AutoEncoders-on-CIFAR10-AND-MNIST-Dataset
 2. Run main.ipynb file
 
 Contribution
If you would like to contribute to this project, please follow these guidelines:

## Fork the repository
  1. Create a new branch for your changes (e.g. feature/new-feature)
  2. Make the necessary changes and commit them
  3. Submit a pull request
   
