# SCT_ML_4
Develop a hand gesture recognition model that can accurately identify and classify different hand gestures from image or video data, enabling intuitive human-computer interaction and gesture-based control systems.

# Leap Gesture Recognition with CNN

This project implements a Convolutional Neural Network (CNN) to recognize hand gestures using the Leap Gesture Recognition dataset. The model is designed to classify ten different gestures, leveraging image preprocessing, data augmentation, and a structured training process.

## Dataset

The dataset consists of grayscale images of hand gestures organized in directories corresponding to each gesture class. The recognized gestures include:
1. Palm
2. L
3. Fist
4. Fist Moved
5. Thumb
6. Index
7. OK
8. Palm Moved
9. C
10. Down

## Features

- **Image Preprocessing**: Images are resized to 50x50 pixels and normalized for model input.
- **CNN Architecture**: A custom CNN architecture with multiple convolutional and pooling layers for effective feature extraction.
- **Training and Validation**: The model is trained using a portion of the dataset, with validation performed on the remaining data.
- **Performance Evaluation**: Model accuracy and loss are plotted, and a confusion matrix visualizes prediction results.

## Requirements

- Python 3.x
- TensorFlow/Keras
- OpenCV
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

## Getting Started

1. Clone the repository.
2. Place the Leap Gesture Recognition dataset in the specified directory.
3. Run the provided Python script to train the model and evaluate its performance.
