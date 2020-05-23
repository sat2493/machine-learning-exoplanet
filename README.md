# machine-learning-exoplanet

Submission for the following [assignment](https://mindful-conscience-812198.netlify.app/21-machine-learning/homework/exoplanet/)

Table of contents
=================

<!--ts-->
   * [Introduction](#Introduction)
   * [Features](#Features)
   * [Python Libraries](#Python-Libraries)
<!--te-->

# Introduction

"""

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, you will create machine learning models capable of classifying candidate exoplanets from the raw dataset.

In this homework assignment, you will need to:

* Preprocess the raw data
* Tune the models
* Compare two or more models

"""

# Features

## Preprocess the Data

* Preprocess the dataset prior to fitting the model.
* Perform feature selection and remove unnecessary features.
* Use MinMaxScaler to scale the numerical data.
* Separate the data into training and testing data.

## Tune Model Parameters
Use GridSearch to tune model parameters.
Tune and compare at least two different classifiers.

# Python Libraries

## Exoplanet Data Source

"""
See [Exoplanet Data Source](https://www.kaggle.com/nasa/kepler-exoplanet-search-results)

This dataset is a cumulative record of all observed Kepler "objects of interest" — basically, all of the approximately 10,000 exoplanet candidates Kepler has taken observations on.

This dataset has an extensive data dictionary, which can be accessed here. Highlightable columns of note are:

kepoi_name: A KOI is a target identified by the Kepler Project that displays at least one transit-like sequence within Kepler time-series photometry that appears to be of astrophysical origin and initially consistent with a planetary transit hypothesis
kepler_name: [These names] are intended to clearly indicate a class of objects that have been confirmed or validated as planets—a step up from the planet candidate designation.
koi_disposition: The disposition in the literature towards this exoplanet candidate. One of CANDIDATE, FALSE POSITIVE, NOT DISPOSITIONED or CONFIRMED.
koi_pdisposition: The disposition Kepler data analysis has towards this exoplanet candidate. One of FALSE POSITIVE, NOT DISPOSITIONED, and CANDIDATE.
koi_score: A value between 0 and 1 that indicates the confidence in the KOI disposition. For CANDIDATEs, a higher value indicates more confidence in its disposition, while for FALSE POSITIVEs, a higher value indicates less confidence in that disposition.
"""

## Scikit-Learn

See [Scikit-Learn](https://en.wikipedia.org/wiki/Scikit-learn)

"""
Scikit-learn (formerly scikits.learn and also known as sklearn) is a free software machine learning library for the Python programming language.[3] It features various classification, regression and clustering algorithms including support vector machines, random forests, gradient boosting, k-means and DBSCAN, and is designed to interoperate with the Python numerical and scientific libraries NumPy and SciPy.
"""

