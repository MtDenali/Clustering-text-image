# Project Title

Data Representations (convert the raw data into feature representa- tions) and Clustering. 

## Table of Contents
- [Project Description](#project-description)
- [Features](#features)
- [Installation](#installation)

## Project Description

Machine learning algorithms are applied to a wide variety of data, including text and images. Before applying these algorithms, one needs to convert the raw data into feature representations that are suitable for downstream algorithms. 

In this project, we explore the concepts of feature extraction and clustering together. In an ideal world, all we need are data points – encoded using certain features– and AI should be able to find what is important to learn, or more specifically, determine what are the underlying modes or categories in the dataset. This is the ultimate goal of General AI: the machine is able to bootstrap a knowledge base, acting as its own teacher and interacting with the outside world to explore to be able to operate autonomously in an environment.

We first explore this field of unsupervised learning using **textual data**. We ask if a combination of feature engineering and clustering techniques can automatically separate a document set into groups that match known labels.

Next we focus on a new type of data, i.e. **images**. Specifically, we first explore how to use “deep learning” or “deep neural networks (DNNs)” to obtain image features. Large neural networks have been trained on huge labeled image datasets to recognize objects of different types from images. For example, networks trained on the Imagenet dataset can classify more than one thousand different categories of objects. Such networks can be viewed as comprising two parts: the first part maps a given RGB image into a feature vector using convolutional filters. Then second part classifies this feature vector into an appropriate category, using a fully-connected multi-layered neural network. 

Such pre-trained networks could be considered as experienced agents that have learned to discover features that are salient for image understanding. Can one use the experience of such pre-trained agents in understanding new images that the machine has never seen before? It is akin to asking a human expert on forensics to explore a new crime scene. One would expect such an expert to be able to transfer their domain knowledge into a new scenario. **In a similar vein, can a pre-trained network for image understanding be used for transfer learning? One could use the output of the network in the last few layers as expert features**. Then, given a multi-modal dataset –consisting of images from categories that the DNN was not trained for– one can use feature engineering (such as dimensionality reduction) and clustering algorithms to automatically extract unlabeled categories from such expert features.

## Features
- Feature 1: Clustering_on_Text_Data.ipynb performs clustering on "20 Newsgroups" dataset.
- Feature 2: Clustering_of_Image_Data_a.ipynb and Clustering_of_Image_Data_b.ipynb perform clustering on tf_flowers dataset.
- Feature 3: Clustering_both_image_text.ipynb uses use the pre-trained Contrastive Language–Image Pretraining (CLIP) to illustrate the idea of multimodal clustering on the Pokedex catalog dataset.

## Installation

Not required.


