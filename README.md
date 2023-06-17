<h1 align="center"> 
  ESRGAN: Enhanced Super-Resolution Generative Adversarial Network
</h1>

<p align="center">
    <a>
        <img src="https://github.com/MadJokkerr/ESRGAN/blob/main/src/Logo.png" width="30%">
    </a>
</p>

## Overview

ESRGAN is an advanced image super-resolution method that leverages deep learning and generative adversarial networks (GANs) to generate high-resolution images from low-resolution inputs. It employs a generator network to transform low-resolution images into high-resolution counterparts, while a discriminator network provides feedback for training and enhancing the visual quality of the generated images.

## Key Features

- Super-resolution: ESRGAN can upscale low-resolution images to higher resolutions, enhancing their visual quality and level of detail.
- Generative Adversarial Network: The GAN framework in ESRGAN incorporates a generator network that generates high-resolution images and a discriminator network that distinguishes between real and generated images.
- Perceptual Loss: ESRGAN employs a perceptual loss function, which measures the perceptual similarity between generated and ground truth high-resolution images using pre-trained deep CNNs. This loss encourages the generation of visually pleasing and realistic results.
- Deep Convolutional Neural Networks: ESRGAN utilizes deep CNNs, such as VGG networks, to capture complex image features and learn the mapping between low-resolution and high-resolution image spaces.
- Python Implementation: ESRGAN is typically implemented using Python programming language and deep learning libraries such as TensorFlow, PyTorch, or Keras.

## Installation
To use ESRGAN, follow these steps:

1. Install Python (version 3.11 or higher): Visit the official Python website (python.org) and download the appropriate installer for your operating system. Follow the installation instructions.
2. Install the required deep learning library: ESRGAN supports multiple deep learning frameworks. Install either TensorFlow, PyTorch, or Keras by following the instructions provided on their respective websites.
3. Download the ESRGAN source code: Visit the official ESRGAN repository on [GitHub](https://github.com/MadJokkerr/ESRGAN) and download or clone the repository to your local machine.

## [Reseach Paper](https://arxiv.org/pdf/2107.10833.pdf)

## Environment Setup
1. Method : 01 
  > (Configured Environmental File)


2. Method : 02 
 > (Installation Using Requirment.txt File)

## Usage
To apply ESRGAN for image super-resolution, follow these steps:

1. Prepare your dataset: Collect a dataset of paired low-resolution and high-resolution images. Ensure that the low-resolution images are appropriately downsampled versions of their high-resolution counterparts.
2. Train the ESRGAN model:
- Preprocess the dataset: Resize the images to the desired low and high-resolution sizes and normalize their pixel values.
- Configure the network: Adjust the hyperparameters and network architecture as needed. Set the number of training epochs, learning rates, batch sizes, etc.
- Train the model: Use the prepared dataset to train the ESRGAN model. Provide the low-resolution images as inputs and the corresponding high-resolution images as ground truth.
3. Generate high-resolution images:
- Load the trained model: Load the trained ESRGAN model weights.
- Preprocess the input image: Resize the input image to the desired low-resolution size and normalize its pixel values.
- Apply ESRGAN: Pass the preprocessed low-resolution image through the generator network to obtain the generated high-resolution image.
4. Post-process the generated image: Apply any desired post-processing steps, such as denoising or sharpening, to further enhance the visual quality.
5. Save or display the result: Save the generated high-resolution image or display it using appropriate tools or libraries.




















## Examples and Results

Include examples of input low-resolution images and their corresponding high-resolution outputs obtained using ESRGAN. Showcase the improved visual quality, enhanced level of detail, and realistic textures achieved by the model.

## Conclusion

ESRGAN is a powerful image super-resolution method that utilizes deep learning, GANs, and perceptual loss to generate high-quality, high-resolution images from low-resolution inputs. By following the installation and usage instructions, you can apply ESRGAN to various applications requiring image upscaling and enhancement.

Please note that this is a sample documentation for ESRGAN and should be customized and expanded according to the specific implementation and requirements of your project.
