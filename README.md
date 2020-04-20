# Glacier Fronts

Glacier Fronts is a Fastai and PyTorch port of [FrontLearning]() a convolutional neural network approach to detecting glacier calving margins in Greenland implemented using Keras.

# Getting started

## Quickstart

[![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/tkristinwilson/glacier-fronts/master)

## Installation
Installation with [conda](https://www.anaconda.com/distribution/) is recommended.

Then launch the `glacier_fronts.ipynb` notebook from [Jupyter Lab](https://jupyter.org).

    git clone https://github.com/tkristinwilson/glacier-fronts
    cd glacier-fronts
    
    conda env create -f environment.yml python=3.8
    conda activate glacier-fronts

    python -m ipykernel install --user --name glacier-fronts
    jupyter nbextension enable --py widgetsnbextension
    jupyter lab &
    
# Citing
