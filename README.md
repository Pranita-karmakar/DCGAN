## DCGAN
DCGAN (Deep Convolutional Generative Adversarial Network). DCGAN is a type of generative model that uses deep convolutional neural networks to generate new data, often used for tasks like image synthesis.I am building a model for generating realistic images, including handwritten digit images from the MNIST dataset. The MNIST dataset is a popular dataset used for training and evaluating machine learning models, especially in the field of computer vision.  
The MNIST database (Modified National Institute of Standards and Technology database) is a large database of handwritten digits that is commonly used for training various image processing systems.

## Pre-requisite[](url)
U need  nvidia Gpu to run this install the NVIDIA_CUDA-<#.#>_Samples then ran several instances of the nbody simulation, but they all ran on one GPU 0; GPU 1 was completely idle (monitored using watch -n 1 nvidia-dmi). Checking CUDA_VISIBLE_DEVICES using
Packages- pytorch with manual seed 42

Run command --echo $CUDA_VISIBLE_DEVICES
## steps[](url)
* Task 1: Setup google runtime
* Task 2: Configurations
* Task 3: Load MNIST handwritten dataset
* Task 4: Load dataset into batches
* Task 5: Create discriminator network
* Task 6: Create generator network
* Task 7: Create loss function and load optimizers
* Task 8: Create training loop to train GAN 

## Configurations [](url)
* Device = cuda
* Batch size = 128
* Noise dim = 64
* learning rate  = 0.0002
  
## Model[](url)
![DCGAN](https://github.com/Pranita-karmakar/DCGAN/assets/134129172/4a511970-4916-4883-af98-c44a609ece87)
* Designing The discriminator
* Designing the Generator
* Creating loss Function
* Loading the optimizer

  
## Outcome[](url)
![mnist](https://github.com/Pranita-karmakar/DCGAN/assets/134129172/6dd630e3-8e6d-486e-a60c-970d56ea94c5)
