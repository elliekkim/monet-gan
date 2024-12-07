# monet-gan

Adam Kosinski and Ellie Kim

### Relevant Files

`cycle_gan_cifar.ipynb` has a short attempt to convert CIFAR10 to Monet, using pure CycleGAN. The image resolution was a bit too low though.

`cycle_gan_lsun.ipynb` has our pure CycleGAN implementation to transform LSUN churches to Monet's style.

`cycle_prog_gan_lsun.ipynb` has our CycleGAN + Progressive Growing GAN implementation to transform LSUN churches to Monet's style.

### Painting Datasets

Monet dataset: https://www.kaggle.com/datasets/dimitreoliveira/monet-paintings-jpg-berkeley

Van Gogh dataset: https://www.kaggle.com/datasets/ipythonx/van-gogh-paintings

See load_data.ipynb for how to download these datsets using kagglehub and create PyTorch Dataset objects for them. This notebook also contains the code to download our 2000 image subset of LSUN churches from a Adam' Duke Box.

