# Image-Classification
Code showing how to build an image classifier with Python and Tensorflow.
Developed a Convolutional Neural Network (CNN) model using TensorFlow and Keras to classify images, incorporating multiple layers (Conv2D, MaxPooling, and Dense) for feature extraction and classification.

Processed and cleaned a dataset of 305 images, eliminating corrupted and non-standard files using OpenCV, and split the dataset into training, validation, and test sets to ensure model accuracy.

Achieved 100% precision, recall, and accuracy on the test dataset after 20 epochs of training, validating the model's high performance in distinguishing between two classes (Happy and Sad).

Deployed the trained model for real-time image predictions, demonstrating the ability to classify unseen images with a binary classification output, and saved the model for future inference using TensorFlow's save_model() functionality.
