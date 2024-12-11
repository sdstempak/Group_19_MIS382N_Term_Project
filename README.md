Project: Anomaly Detection from Surveillance Footage

Group Members: Scott Stempak, Mason Shu, Theresa Sushil, Gauruv Shukla, and Pratyush Rohilla

### This repository contains the implementation of an anomaly detection model for analyzing surveillance videos using deep learning techniques. This was done in regards to the term project for the Advanced Machine Learning Course that we undertook during our Masters in Business Analytics program at The University of Texas at Austin, McCombs School of Business (2024).

## Introduction
Anomaly detection in surveillance footage is a critical task for enhancing safety and security in public and private spaces. In this implementation, we explore how a derived dataset from the UCF Crime Dataset is used to train a machine-learning model for detecting anomalous events. The model leverages deep learning techniques, including Convolutional Neural Networks (CNNs) and Transformer-based models, to detect anomalies in surveillance footage.

## Dataset
We use a Kaggle dataset derived from the UCF Crime Dataset, which contains 1,900 untrimmed surveillance videos spanning 13 anomaly classes. Videos are labeled at the video level for weakly supervised learning. The data contains approximately 128 hours of footage. 1610 of these videos are normal videos, while 290 are anomalies. The videos are grouped into 13 anomaly classes: Abuse, Arrest, Arson, Assault, Road Accident, Burglary, Explosion, Fighting, Robbery, Shooting, Stealing, Shoplifting, and Vandalism, along with a Normal class representing non-anomalous activities.

## Model Architecture
The model uses a hybrid architecture for feature extraction of the video frames and for creating the temporal sequence among the frames:

Feature Extraction - ResNet18 for spatial feature extraction.

Temporal Modeling - Causal Transformer for temporal relationships between frames.


For more information please refer to our medium article: https://medium.com/@sdstempak14/analyzing-surveillance-videos-to-detect-crime-aa337a7430f2 
