<h1 align="center"> Image Generation with Autoencoder and GAN </h1>

This project demonstrates image generation using an autoencoder and Generative Adversarial Network (GAN) architecture. The autoencoder consists of two main parts: an encoder and a decoder, while the GAN consists of a generator and a discriminator. We use the CIFAR-10 dataset available in keras.datasets, which contains 60,000 color images of 32x32 pixels, divided into 10 classes.

<h3 align="left">Autoencoder Structure </h3>
Encoder
The encoder part compresses the input image into a lower-dimensional representation. 
The decoder part reconstructs the image from the encoded representation. 

<h3 align="left" >Utilizing Generative Adversarial Network (GAN)</h3>
The GAN consists of two models, the generator and the discriminator, where the generator creates images intended to be indistinguishable from real images, and the discriminator tries to differentiate between real and generated images.
<br>
<br>
<p align="left"><strong>Generator</strong></p>
Built with Conv2DTranspose layers and LeakyReLU activations, ending with a Conv2D layer using 'tanh' activation to generate images.
<br>
<br>
<p align="left"><strong>Discriminator</strong></p>
Composed of Conv2D layers and LeakyReLU activations, ending with a Dense layer using 'sigmoid' activation to classify images as real or fake.

<h3 align="left"> Requirements </h3>
<ul>
<li>Python 3.x</li>
<li>TensorFlow 2.x</li>
<li>Keras</li>
<li>Matplotlib</li>
</ul>
