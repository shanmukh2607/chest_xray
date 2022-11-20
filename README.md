# Lossless Image Compression for Medical Images using Neural Networks
By, Bachotti Sai Krishna Shanmukh, Undergraduate in Department of Electrical Engineering, IIT Madras <br>
Professor : Nitin Chandrachoodan

## Project Abstract
Medical Images are used in healthcare to diagnose certain health conditions and often require a very
accurate pixel map for computer-aided diagnosis. These images are also used as datasets for both
supervised (or) unsupervised deep learning models to diagnose critical health conditions, analyze the
nature and spread of tumors etc. Hence, compressing these images in a lossless way i.e., capturing the
complete information present in the original pixel map into a lower file size configuration is critical
for accurate diagnosis. In this paper, we discuss about using Neural Networks for lossless image
compression.

## Repository structure
This repository contains the code of four autoencoder models, weights and results. <br>

NN : Folder for ANN based Autoencoder trained on MSE loss
CNN : Folder for CNN based Autoencoder trained on MS_SSIM based loss
CNN2 : Folder for CNN based Autoencoder with increased latent space dim and trained on custom loss 
CNN3: Dual Stage Autoencoder
HiFiC : Pre-Trained GAN model compression bit-rate

Dataset : Kaggle Chest X-ray Dataset

