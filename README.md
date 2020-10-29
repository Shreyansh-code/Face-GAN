# FACE-GAN
This project's aim is to generate fake but real looking images of humans. 
## What are GANs?
Generative Adversarial Networks (GANs) are one of the most interesting ideas in computer science today. Two models are trained simultaneously by an adversarial process. A generator ("the artist") learns to create images that look real, while a discriminator ("the art critic") learns to tell real images apart from fakes.

![](https://github.com/tensorflow/docs/raw/be8ac03d73a77d3b71ba2b42849d2169c1d7d100/site/en/tutorials/generative/images/gan1.png)
During training, the generator progressively becomes better at creating images that look real, while the discriminator becomes better at telling them apart. The process reaches equilibrium when the discriminator can no longer distinguish real images from fakes.

![](https://github.com/tensorflow/docs/raw/be8ac03d73a77d3b71ba2b42849d2169c1d7d100/site/en/tutorials/generative/images/gan2.png)

### Face-GAN Model description
* Dataset used - CelebA 
* Training dataset size - 50000
* Noise - 100
* Optimizer - adam
* Loss - binary crossentropy 
* Epochs - 300
* Batch size - 128
Training of the model took more than 2 and half hours

## Disclaimer
This model generates images which looks like a human face but is no way near realistic due to the low number of epochs which is set to 300 because it would take very long(days infact)on local machine to get realistic image .With higher epochs and fine tuning the model will result in better result.
