# How can I install Tensorflow locally?

### Prerequisite:
- Conda environment set up and able to run notebooks locally (see [guideline](../run-jupyter-notebooks-locally))

### Steps

We recommend creating a new Conda environment for this exercise using Python 3.11 as the TensorFlow exercises in this repository have been tested with this Python version.

1. Create a new Conda environment using Python 3.11 (e.g. hhz-py311-tf)
2. Install the latest version of the Jupyter notebook package ("notebook") and launch it


### Install tensorflow and other libraries

1. Open a notebook and install tensorflow and other required libraries via *pip* by executing code cells below:
```python
# pinned to latest versions as per May 2024
! pip install tensorflow==2.16.1
! pip install tensorflow-datasets==4.9.4
! pip install tensorflow-hub==0.16.1
! pip install matplotlib==3.8.4
! pip install ipywidgets==8.1.2
```
2. Restart your kernel (via Kernel > Restart)
3. Check the installed Tensorflow versions
```
import tensorflow as tf
print(tf.__version__)

import tensorflow_datasets as tfds
print(tfds.__version__)
```

