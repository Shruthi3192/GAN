# GAN
Experimenting with GANs

This projects uses MNSIT hand written images of numbers.
It uses the DCGAN technique for implementation.
This project is inspired by 

Radford, A., Metz, L., & Chintala, S. (2015). Unsupervised representation learning with deep convolutional generative adversarial networks. 
arXiv preprint arXiv:1511.06434.
https://arxiv.org/abs/1511.06434
This paper explains working with Deep Convolutional Generative Adversarial Networks

The end result of the generation can be seen in the output file TensorBoard_output.JPG

This technique uses Discriminator and Generator networks. The Generator network is built from noise of dimension 256.
The images used for this project is grey scale images hence number of channels of the input and output images are 1.
