# Variational Autoencoders (VAE)
In this notebook I explore variational Autoencoders (VAE) with Mnist's fashion dataset. Variational autoencoders are meant to compress the input information into a constrained multivariate latent distribution (encoding) to reconstruct it as accurately as possible (decoding). 

<img src='images/vae.png' width='800'>

So the model learns the dataset which contains images of different clothes. The objective is to reconstruct the image using mean and variance of desired output. Two different loss functions are used which is finally combined into one total loss function. If we want to reconstruct an image of a particular piece of clothes than we can first enocode the respective image to get the values of mean and variance and using these values later it is possible to decode it and reconstruct and image. The result is given below.

<img src='images/dres.png' width='800'>
