# WaveNet-colab

This is a slightly modified version of [A TensorFlow implementation of DeepMind's WaveNet paper](https://github.com/ibab/tensorflow-wavenet) to be run in Google Colaboratory, using Google Drive as data storage. See [the original repository](https://github.com/ibab/tensorflow-wavenet) for details.

## Modifications

- 44.1 kHz sample rate and other default settings

## Current bugs

- Due to prerequisition version mismatches in Colab, this is currently unable to continue training from any previous checkpoint. Though it may come as consolation that you can exit Colab and leave it running, easily achieving 1e5 steps in one go.

## Run in Google Colaboratory
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/WaveNet-colab/blob/master/WaveNet.ipynb)
