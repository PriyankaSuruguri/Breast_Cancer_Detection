# Breast Tumor Detection with Deep Learning
## Overview
This project focuses on Breast Tumor Detection using deep learning models, with a focus on mammogram images. The objective is to develop a model capable of accurately classifying mammograms into benign and malignant tumor categories, helping in the early detection of breast cancer. The project utilizes a set of mammogram images containing annotated breast tumor data. By applying convolutional neural networks (CNNs) and other advanced deep learning techniques, the goal is to improve the model's accuracy and robustness in detecting breast tumors.

## Abstract
Breast cancer is one of the leading causes of death among women worldwide. Early detection through automated systems can significantly improve survival rates. This project explores the use of deep learning models to detect and classify tumors in mammogram images. The dataset contains images labeled as benign or malignant, which are used to train and evaluate the performance of convolutional neural networks (CNNs).

## Key Features
- Dataset: The dataset consists of 3,383 mammogram images annotated with two categories: benign and malignant. These images are preprocessed for use in deep learning models.
- Model Architecture: The project uses a Convolutional Neural Network (CNN) to extract features from mammogram images and classify them into benign or malignant categories.
- Data Preprocessing:
- Auto-orientation: EXIF orientation metadata is stripped to ensure correct image orientation.
- Resizing: Images are resized to 640x640 pixels to ensure consistency and compatibility with the model.
- Loss Function & Metrics: Binary cross-entropy loss is used, and the model’s performance is evaluated using accuracy as the primary metric.
- Handling Class Imbalance: Techniques like weighted loss functions and data augmentation (e.g., rotations, flipping) are applied to manage class imbalance and improve model generalization.
