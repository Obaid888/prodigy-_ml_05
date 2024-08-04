Dataset:
Utilized the Food-101 dataset from Kaggle, which contains over 100,000 images of food items across 101 categories.

Preprocessing:
Images were resized to a consistent size of 150x150 pixels and normalized.
Data augmentation techniques such as rotation, zoom, and horizontal flip were applied to increase the diversity of the training data.

Model Architecture:
Constructed a Convolutional Neural Network (CNN) for feature extraction and classification.
The model includes multiple convolutional layers followed by max-pooling layers, a flatten layer, and dense layers for the final classification.

Training:
The model was trained using a combination of training and validation sets to monitor performance and avoid overfitting.

Evaluation:
Achieved impressive accuracy in recognizing various food items.
Evaluated the model using validation data, focusing on both classification accuracy and calorie estimation.

This project showcases the potential of deep learning in health and wellness applications. By accurately recognizing food items and estimating their calorie content, this model enables users to effortlessly track their dietary intake and make informed decisions about their food choices.
