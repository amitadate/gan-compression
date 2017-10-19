# DCGAN in TensorFlow

TensorFlow / TensorLayer implementation of [Deep Convolutional Generative Adversarial Networks](http://arxiv.org/abs/1511.06434) which is a stabilize Generative Adversarial Networks.

Looking for Text to Image Synthesis ? [click here](https://github.com/zsdonghao/text-to-image)

![alt tag](img/DCGAN.png)




## Prerequisites

- Python 2.7 or Python 3.3+
- [TensorFlow==1.0+](https://www.tensorflow.org/)
- [TensorLayer==1.4+](https://github.com/zsdonghao/tensorlayer)


## Usage

First, download images to `data/celebA`:

    $ python download.py celebA		[202599 face images]

Second, train the GAN:

    $ python main.py

## Result on celebA


<a href="http://tensorlayer.readthedocs.io">
<div align="center">
	<img src="img/result.png" width="90%" height="90%"/>
</div>
</a>
