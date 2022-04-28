

# Simple Implementation of Residual Quantizer and RQ-VAE

RQ-VAE (Residual-Quantized Variational Autoencoder) is a modification of VQ-VAE (Vector Quantized-Variational Autoencoder).

RQ-VAE is proposed in [this paper](https://arxiv.org/abs/2203.01941). Its official implementation is found in [the link](https://github.com/kakaobrain/rq-vae-transformer).

Here, we provide a very simple implementation of RQ-VAE and residual quantization therein.

The implmentation here is laregly based on the [colab implementation](https://colab.research.google.com/github/zalandoresearch/pytorch-vq-vae/blob/master/vq-vae.ipynb#scrollTo=yAzAH7FIb7Tf) of VQ-VAE.


## Requirements
- Pytorch 1.8.2
