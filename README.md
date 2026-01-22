# Auto-Encoder-with-Regression-for-Time-Series-Anomaly-Detection

## Overview

This repository provides a from-scratch PyTorch implementation of the *Auto-Encoder with Regression (AER)* framework for univariate time-series anomaly detection, as proposed in:

> *Auto-Encoder with Regression for Time-Series Anomaly Detection* (2022)

The implementation follows the methodological descriptions and equations presented in the original paper, without relying on the authors’ reference codebase.

The original implementation released by the authors as part of the `orion-ml` library is based on TensorFlow/Keras and is currently incompatible with recent Python versions and Google Colab environments. This repository addresses these limitations by offering a fully self-contained PyTorch implementation compatible with modern Python versions, enabling reproducible experimentation in contemporary research workflows.

In addition to faithfully reproducing the core AER methodology, this implementation explores alternative post-processing strategies, with a particular focus on thresholding procedures for anomaly score interpretation. The codebase is structured in a modular manner to facilitate experimentation, inspection of intermediate outputs, and adaptation to different univariate time-series datasets.

