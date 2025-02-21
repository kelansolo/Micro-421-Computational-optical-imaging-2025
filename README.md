# Computational Optical Imaging - MICRO-421 

[Computational Optical Imaging](https://edu.epfl.ch/coursebook/en/computational-optical-imaging-MICRO-421) is taught by [Demetri Psaltis](https://people.epfl.ch/demetri.psaltis/?lang=en).
The teaching assistant are [Ilker Oguz](https://people.epfl.ch/ilker.oguz), [Ulas Dinc](https://people.epfl.ch/niyazi.dinc) and [Felix Wechsler](https://people.epfl.ch/felix.wechsler)
For official information see [the course Moodle](https://moodle.epfl.ch/).

This repository just provides the source code for the homework.

## Installation of packages
For example, download [Anaconda](https://www.anaconda.com/download/success) as a Python package manager.
(There is many alternatives, just go for one which you prefer.)

In your Python environment, install at least the following packages:
```
pip install numpy matplotlib scipy notebook ipywidgets imageio
```

Later, we also need the following packages for [PyTorch](https://pytorch.org/):
```
pip3 install torch torchvision --index-url https://download.pytorch.org/whl/cu118
```


## Alternatives
You can also the free service [Google Colab](https://colab.research.google.com/). Colab also provides limited amount of GPU usage which is useful for deep learning tasks as GPUs are much faster than CPUs for training neural networks.
