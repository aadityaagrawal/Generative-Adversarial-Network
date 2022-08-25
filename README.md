# Generative-Adversarial-Network

A game between two players- Generator(G) vs Descriminator(D)

MNIST-GAN is a simple Generative Adversarial Network that learns how to generate images that look like human written digits. The idea is to train a "generator" network which when fed noise (in my case a 100 dimensional random vector) will generate an image that looks like a human written digits. Mind bending! Below are the images that shows how the output of the digits generated after 50 epochs. You can see how the digit starts to take shape from the noise:

![alt text](https://github.com/aadityaagrawal/Generative-Adversarial-Network/blob/main/MNIST%20GANS/generated%20image/image_at_epoch_0001.png "random image")                ![alt text](https://github.com/aadityaagrawal/Generative-Adversarial-Network/blob/main/MNIST%20GANS/generated%20image/image_at_epoch_0050.png "image after 50 epochs")

# Dataset 
* For training we are using mnist dataset
* It was constructed from NIST's Special Database 3 and Special Database 1 which contain binary images of handwritten digits.
* It contain 60,000 training cases and 10,000 test cases of handwritten digits (0 to 9)
* Each digit is normalized and centered in a gray-scale (0 - 255) image with size 28 × 28.
* Each image consists of 784 pixels that represent the features of the digits.
* To scale the dataset values between -1 and +1 we subtract and divide it by 127.5
* Then we divided the dataset into batches of 64 for faster training.

# Generator Model
![alt text](https://github.com/aadityaagrawal/Generative-Adversarial-Network/blob/main/MNIST%20GANS/model%20structure/generator_plot.png "Generator Model")

# Discriminator Model
![alt text](https://github.com/aadityaagrawal/Generative-Adversarial-Network/blob/main/MNIST%20GANS/model%20structure/discriminator_plot.png "Generator Model")

# Output
https://user-images.githubusercontent.com/74168474/186491354-e4092a38-01a7-4fc5-8d11-a902faed5917.mp4

