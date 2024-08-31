# NLP Classifier: Visualizing Insights with TensorBoard

This repository contains the code and resources for the blog article [**"NLP Classifier: Visualizing Insights with TensorBoard"**](link-to-your-blog), published on Medium. The project focuses on building an NLP classifier for Quora questions and visualizing classified words using TensorBoard.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Visualization with TensorBoard](#visualization-with-tensorboard)
- [Dataset](#dataset)
- [Cloning](#Cloning)

## Overview

This project demonstrates how to build a natural language processing (NLP) classifier using TensorFlow and how to visualize the word embeddings using TensorBoard. The classifier is trained on Quora question pairs to distinguish between similar and dissimilar questions. The embeddings generated during training are visualized to gain insights into how the model interprets different words and phrases.

## Features

- **NLP Classifier:** Classifies Quora questions into similar and dissimilar categories.
- **TensorBoard Integration:** Visualizes word embeddings and training metrics.
- **Custom Dataset Support:** Easily adaptable to other datasets.




## Visualization with TensorBoard

This project uses TensorBoard to visualize word embeddings and other training metrics. After training the model, embeddings are projected into a lower-dimensional space and visualized on TensorBoard. This allows you to observe how the model clusters similar words and separates dissimilar ones.

![TensorBoard Visualization](https://projector.tensorflow.org/)

## Dataset

The dataset used in this project is the Quora Question Pairs dataset. You can download it from [https://archive.org/](https://archive.org/download/fine-tune-bert-tensorflow-train.csv/train.csv.zip) and place it in the `data/` directory.


## Cloning

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/nlp-classifier-tensorboard.git
    cd nlp-classifier-tensorboard
    ```
