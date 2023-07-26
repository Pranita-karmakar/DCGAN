## DCGAN
DCGAN (Deep Convolutional Generative Adversarial Network). DCGAN is a type of generative model that uses deep convolutional neural networks to generate new data, often used for tasks like image synthesis.I am building a model forgenerating realistic images, including handwritten digit images from the MNIST dataset. The MNIST dataset is a popular dataset used for training and evaluating machine learning models, especially in the field of computer vision.  

## Pre-requisite[](url)
U need  nvidia Gpu to run this install the NVIDIA_CUDA-<#.#>_Samples then ran several instances of the nbody simulation, but they all ran on one GPU 0; GPU 1 was completely idle (monitored using watch -n 1 nvidia-dmi). Checking CUDA_VISIBLE_DEVICES using

Run command --echo $CUDA_VISIBLE_DEVICES


## Configuration [](url)
* Device = cuda
* Batch size = 128
* learning rate  = 0.0002
  
## Model[](url)
![DCGAN](https://github.com/Pranita-karmakar/DCGAN/assets/134129172/4a511970-4916-4883-af98-c44a609ece87)
