# My Squash Data

This project serves as a public repository for the dataset consisting of self-tracked data of my squash training and performance progress, as well as Colab notebooks that do stuff with it.

The dataset contains data starting from 2019 and is updated daily. It is a highly sparse matrix that needs some aggregation for being used with most of the traditional statistical/ML approaches; [weight_predictor.ipynb](https://github.com/emarock/my-squash-data/blob/main/weight_predictor.ipynb) shows one way to do that.

## Contents

 * [data.csv](https://github.com/emarock/my-squash-data/blob/main/data.csv): the nightly updated dataset
 * [weight_predictor.ipynb](https://github.com/emarock/my-squash-data/blob/main/weight_predictor.ipynb) ([Colab link](https://colab.research.google.com/github/emarock/my-squash-data/blob/main/weight_predictor.ipynb)): an adaptation of the [Tensorflow Time series forecasting tutorial](https://www.tensorflow.org/tutorials/structured_data/time_series) that trains a bunch of models and uses them to make predictions of future body weight values
