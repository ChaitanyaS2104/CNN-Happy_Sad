# Happy-Sad Image Classifier using CNN
 
A Convolutional Neural Network (CNN) built using Python and TensorFlow/Keras to classify facial expressions as **happy** or **sad** based on image input.

## Overview

This project trains a deep learning model to distinguish between happy and sad faces using a dataset of labeled facial images. The model is trained, validated, and tested on image data and is capable of predicting the emotion shown in unseen images.

---

The data was sourced from - https://www.kaggle.com/datasets/billbasener/happy-sad-images.

## Model Architecture

- Input Layer: 256x256 RGB images
- Convolutional Layers (Conv2D + MaxPooling)
- Flatten
- Dense Layer `relu` activation
- Output Layer with `sigmoid` activation (binary classification)

Loss function: `binary_crossentropy`  
Optimizer: `Adam`  
Metric: `accuracy`

<img width="400" alt="image" src="https://github.com/user-attachments/assets/deb739e7-3406-4223-ba72-5e7370f9146d" />
<img width="400" alt="image" src="https://github.com/user-attachments/assets/3de8f60e-b36b-4970-aa48-5ad549730a60" />
