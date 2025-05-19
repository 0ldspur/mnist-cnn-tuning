# mnist-cnn-tuning
# MNIST CNN Model – Improved Accuracy with Simple Tuning

This project is about improving a basic CNN (Convolutional Neural Network) model trained on the MNIST dataset (handwritten digits). The original model had a test accuracy of around **95.72%**, and the goal was to tune the model to get **better results**.

- What Was Done

The following changes were made to improve the model:

- Increased the number of filters in the CNN layers to help the model learn better features.
- Changed the kernel size from `(7x7)` to `(3x3)` for more effective learning.
- Added **Batch Normalization** to make training more stable and faster.
- Added one more CNN layer to make the model deeper.
- Used **ReduceLROnPlateau**, a callback that reduces the learning rate automatically when progress slows down.

## Final Result

- The improved model reached a **test accuracy of 99.26%**, using only 10 training epochs.
- This shows how small changes can make a big difference in deep learning.

## Dataset

- MNIST dataset (loaded using Keras)

## Tools Used

- TensorFlow / Keras
- Python 3.x
- Google Colab / Jupyter Notebook
