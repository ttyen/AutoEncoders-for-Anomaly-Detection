# AutoEncoders-for-Anomaly-Detection

This is a jupyter Notebook that where I use a Neural Network model, namely Autoencioders for detecting anomallies in my data.
Original blog: https://blog.goodaudience.com/neural-networks-for-anomaly-outliers-detection-a454e3fdaae8

**Libraries & Respective Versions:**

**Numpy version      : 1.14.2**

**Pandas version     : 0.22.0**

**Matplotlib version : 2.0.2**

**Seaborn version    : 0.7.1**

**Plotly version     : 2.7.0**

**Tensorflow version : 1.8.0**

**Keras version      : 2.2.0**

## remove previous miniconda environment if existed
conda remove --all -n autoencoder
#
conda env create -f environment.yml
## after create anaconda environment disable pluging to supress warning
# disable .jupyter plugin "jupyter_tensorboard": false
