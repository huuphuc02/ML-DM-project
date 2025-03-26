# Machine Learning for Malware Detection in IoT Networks

This repository contains the implementation for a project focused on applying machine learning techniques to detect malware in IoT network traffic data.

## Overview

This Jupyter notebook analyzes the IoT-23 dataset to develop and evaluate various machine learning models for detecting malicious traffic in IoT networks. The implementation includes both supervised learning approaches (classification) and unsupervised learning methods (clustering) to identify different types of attacks.

## Dataset

The IoT-23 dataset consists of network traffic collected from IoT devices under both normal and malicious scenarios, including:

- 23 labeled scenarios (20 malicious, 3 benign)
- Malware types: Hakai, Hide and Seek, and Mirai
- Attack categories: Command & Control (C&C), DDoS, and Horizontal Port Scans
- Over 1 million samples with 21 features

Due to computational constraints, a subset of the full dataset (1,044,258 samples) was used for this project.

## Notebook contents

The notebook includes the following components:

1. **Dataset collection**
2. **Data preprocessing**
3. **Data anylysis & Visualization**
4. **Classification Models**:
  - XGBoost
  - Random Forest
  - Naive Bayes
  - Support Vector Machine
5. **Clustering methods**:
  - K-means clustering
  - Hierarchical clustering

## Usage

You can run this notebook by:

1. Viewing it directly in Google Colab:
  [Open in Google Colab](https://colab.research.google.com/drive/1KW2GUVYvvtUoQTqJov5bVmbEpHQ49N?usp=sharing)

2. Or downloading the notebook and running it locally:
  - Make sure you have Python 3.8+ with Jupyter installed
  - Install requirements: `pip install scikit-learn<1.6 numpy pandas matplotlib seaborn xgboost`
  - Launch Jupyter and open the notebook

## Requirements

- Python 3.8+
- scikit-learn < 1.6 (or XGBoost built from GitHub)
- numpy
- pandas
- matplotlib
- seaborn
- xgboost

## Authors

- Huu Phuc CHU
- Ngoc Khanh DAM

## Acknowledgments
This project was created as part of the Machine Learning and Data Mining course at Université Clermont Auvergne.
