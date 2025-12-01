# U-Net Implementation for Image Segmentation



## Introduction

This notebook provides a complete implementation of the U-Net architecture for image segmentation tasks. It covers the definition of the U-Net model, data loading and preprocessing, and sets up the environment for training a deep learning model using PyTorch.



## Model Architecture



### Convolutional Block (conv function)

This function defines a standard convolutional block used throughout the U-Net architecture. Each block consists of two convolutional layers, each followed by Batch Normalization and a ReLU activation function.



### U-Net Class Definition

This class defines the UNet architecture, implementing the complete U-Net architecture. 



## Data Preparation



### Mount Google Drive

This step mounts Google Drive to the Colab environment. This is essential for accessing dataset files stored in your Google Drive.



### Define Data Directories

This section defines the directory paths for the image and mask data. These paths point to the locations within Google Drive where the CameraRGB (input images) and CameraMask (segmentation masks) folders are stored.




### Data Transformations and Dataset Initialization

This cell defines image and mask transformations (resizing, converting to tensor, normalization). It also defines the UNetDataset class for loading images and masks, and then initializes the dataset and DataLoader for batching data during training.
