# Detection-and-recognition-of-traffic-signs
# Overview
This project involved developing machine learning models to recognize and classify traffic signs from images in the German Traffic Sign Recognition Benchmark (GTSRB) dataset. The goal was to build an accurate image classifier that can automatically detect and identify different types of traffic signs.


# Dataset
The GTSRB dataset contains over 50,000 images of 43 different classes of traffic signs. The images have varying sizes and were captured under different lighting, angle, and distance conditions, making it a challenging real-world computer vision task.

The dataset is split into training and test sets:

Training set: 39,209 images
Test set: 12,630 images
Each image has a corresponding label indicating the class of traffic sign depicted. The 43 classes include speed limits, no entry, stop signs, and more.

# Methods
The project involved the following steps:

Data preprocessing - Resizing images, converting to grayscale, normalization, etc.
Augmentation - Generating additional training images via rotations, shifts, etc.
Feature extraction - Using convolutional neural networks to learn feature representations
Model training - Training classifiers like SVM, random forests, and neural networks
Evaluation - Assessing model accuracy, precision, recall on test data
Two models were implemented and compared:

PyTorch CNN
TensorFlow CNN
Hyperparameter tuning was performed to optimize each model.

# Results
The models achieved the following test accuracy:

PyTorch CNN: 94.37%
TensorFlow CNN: 95.30%
Additional evaluation metrics like precision, recall, and F1-score were computed for each class.

The TensorFlow model performed slightly better overall. Both models had some difficulty with certain classes with fewer training examples.

# Conclusion
This project demonstrated that machine learning, particularly convolutional neural networks, can accurately classify traffic signs from images taken in real-world conditions. The models and techniques explored could be applied to improve road safety through automated traffic sign recognition.

Future work could focus on generating more balanced and higher quality training data, as well as investigating more complex deep learning architectures.


