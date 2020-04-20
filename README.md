# Glacier Fronts

Glacier Fronts is a `fastai v1` (PyTorch) port of [FrontLearning](https://github.com/yaramohajerani/FrontLearning) - a convolutional neural network used to detect glacier calving margins in Greenland, originally implemented using Keras.

**This is an initial port only and has not yet been tuned.**

## Quickstart

[![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/tkristinwilson/glacier-fronts/master) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/tkristinwilson/glacier-fronts/blob/master/glacier_fronts.ipynb)


## Installation
Installation with [conda](https://www.anaconda.com/distribution/) is recommended.

Then launch the `glacier_fronts.ipynb` notebook from [Jupyter Lab](https://jupyter.org).

    git clone https://github.com/tkristinwilson/glacier-fronts
    cd glacier-fronts
    
    conda env create -f environment.yml
    conda activate glacier-fronts

    python -m ipykernel install --user --name glacier-fronts
    jupyter nbextension enable --py widgetsnbextension
    jupyter lab &
