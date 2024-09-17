# ML Projects (Capstone)

## Description
This project aims to reproduce and enhance the performance of the pre-trained model modified in the paper “An Approach to Run Pre-Trained Deep Learning Models on Grayscale Images” by incorporating data augmentation techniques. The project will explore various strategies like rotation, flipping, and scaling to diversify the training data and enhance model generalization.

### Overview
- **Original Paper Overview**: The paper enhanced the VGG16 model for binary classification of grayscale images by adapting the weight initialization of its first hidden layer, achieving performance close to that of models trained on RGB images.
- **Problem Statement**: The study did not explore data augmentation as a way to improve generalization. Grayscale images lack color information, which may limit the model’s ability to generalize effectively. The original work did not investigate how data augmentation could address this limitation.
- **Proposed Improvement**: By applying data augmentation techniques like rotation, flipping, and cropping, this project aims to improve the VGG16 model's performance on grayscale images. Increasing the diversity of training data can help reduce overfitting and improve generalization.
- **Impact of Improvement**: Incorporating data augmentation is expected to improve the model’s classification accuracy and generalization, particularly in smaller datasets, making the model more robust.

### Original Paper Reference
[1] I. Ahmad and S. Shin, “An Approach to Run Pre-Trained Deep Learning Models on Grayscale Images.” 2021 IEEE International Conference on Artificial Intelligence in Information and Communication, Apr. 2021. DOI: [10.1109/icaiic51459.2021.9415275](https://doi.org/10.1109/icaiic51459.2021.9415275).

## Project Scope
1. **Replication**: Reproduce the results presented in Section III of the original paper using the Dogs vs. Cats dataset.
2. **Performance Enhancement**: Implement and evaluate different data augmentation techniques.
3. **Comparison**: Compare the model’s performance with and without data augmentation.

## Technology Stack
- **Frameworks**: Keras, TensorFlow
- **Programming Language**: Python
- **Hardware**: Google Colab
- **Dataset**: Dogs vs. Cats dataset (converted to grayscale) dataset link: https://www.kaggle.com/competitions/dogs-vs-cats/data
