
## our experiments with image compression technique with added stabilization by added optimization using generative adversatial network.

## Architecture

![alt tag](CompressionArchitecture.jpg)

## Prerequisites

- Python 2.7 or Python 3.3+
- [TensorFlow==1.0+](https://www.tensorflow.org/)
- [TensorLayer==1.4+](https://github.com/zsdonghao/tensorlayer)


## Usage

First, download images to `data/celebA`:

    $ python download.py celebA		[202599 face images]

Second, train the GAN:

    $ python train_compression.py
