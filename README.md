
## Our experiments with image compression with added stabilization by intergrating with a generative adversarial network.

## Architecture

![alt tag](CompressionArchitecture.jpg)

## Prerequisites

- Python 2.7 or Python 3.3+
- [TensorFlow==1.0+](https://www.tensorflow.org/)
- [TensorLayer==1.4+](https://github.com/zsdonghao/tensorlayer)


## Usage

First, download images to `data/mnist`:

    $ python download.py mnist		[202599 face images]

Second, train the GAN:

    $ python train_compression.py
