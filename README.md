# GAN
A Generative Adversarial Network developed to generate images of plutonic rocks (the most abundant rocks in the Earth's upper crust). The produced images are intended to be applied to classification models to improve training and testing and to mitigate overfitting.

The presented model generates 512x512 pixel images. The generated images and the model are saved every 20 epochs. The discriminator loss and generator loss are displayed for each step, and the accuracy is calculated every 10 epochs.

The quality of the generated images in comparison to the original/real images can be evaluated by calculating the Frechet Inception Distance Score (FID Score). The code for the calculation of the FID score is also provided to evaluate the images.
