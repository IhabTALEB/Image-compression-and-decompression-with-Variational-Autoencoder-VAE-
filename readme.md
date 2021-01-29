# Image compression and decompression with Variational Autoencoder (VAE)
This repository consists of compressing and decompressing images using VAE, the model was trained using the [LSUN bedroom scene 20% sample](https://www.kaggle.com/jhoward/lsun_bedroom/data) dataset from Kaggle, in This repo you can find the code in a notebook named **VAE.ipynb**, training images were resized to (64,64), the same notebook can be found on Google Colab by clicking on this [Link](https://colab.research.google.com/github/IhabTALEB/Image-compression-and-decompression-with-Variational-Autoencoder-VAE-/blob/master/VAE.ipynb). Samples are in the following picture.

<p align="center">
  <img src="/samples/output sample.png" />
</p>

Please note that the decompressed images can be brighter with more training data. I was able to train on 50000 images only due to Google Colab's limitations.

In order to run this code on Colab, you need to download your kaggle.json file from the [Kaggle](https://www.kaggle.com/) Webiste, save it in your Google Drive, and change the path of this file in the Section "Prepare Kaggle CLI" in the notebook.
