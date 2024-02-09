# Prospace

  PROSPACE: Satellite Image Analysis

First we have preprocessed the data to find that average size if 4*36*36

We convert image data to tensor

Then we used Variational autoencoder using CNN:

This model encode tensor image to lower dimension then decode it back to original dimension.

This model is widely used to remove noise and to get latent vector which is the bottleneck which has lower dimension.

So basically we used this latent vector to clustering

We used Gaussian mixture model for cluster 

A Gaussian mixture model is a probabilistic model that assumes all the data points are generated from a mixture of a finite number of Gaussian distributions with unknown parameters.

this model uses latent vector obtained from VAE and cluster them into 3 classes
