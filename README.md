# Data Processing in a Big Data Cloud Environment

## Data Source

Data can be downloaded from: [Kaggle Fruits Dataset](https://www.kaggle.com/datasets/moltean/fruits)

## Project Overview

An AgriTech start-up is developing smart fruit-picking robots. The goal is to create a mobile app that identifies fruits from photos and provides information about them.

## Objectives

1. **PySpark Scripts**:
   - Develop PySpark scripts for data processing and prepare for scaling.

2. **Broadcasting TensorFlow Weights**:
   - Implement model weight broadcasting for distributed inference using TensorFlow Keras.

3. **PCA/TSNE Reduction**:
   - Include PCA dimensionality reduction in PySpark.
   - Use TSNE for visualizations to evaluate feature extraction/reduction effectiveness and its impact on classification.

## Cloud Setup

- Use AWS for all processing in the cloud.
  - **EMR**: Set up for Big Data processing.
  - **EC2**: Configure for compute needs.
  - **S3**: Store data and results.

## Compliance

- Adhere to GDPR by configuring servers in the European region.

## Notebooks

1. **Notebook 1**: PySpark scripts for testing on a local machine.
2. **Notebook 2**: Notebook for running all operations using EC2 and S3, with no local processing.
3. **Notebook 3**: TSNE visualizations to assess the usefulness of feature extraction/reduction and its impact on classification.
