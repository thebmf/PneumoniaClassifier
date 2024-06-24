# PneumoniaClassifier

### This project utilizes deep learning to classify chest X-ray images as either normal or containing pneumonia.

## Purpose:

To develop a deep learning model for classifying pneumonia in chest X-ray images.

To evaluate the model's performance on a dataset of chest X-ray images.

To provide a framework for further analysis and improvement of the model.

## Functionality:

Loads and preprocesses chest X-ray images from a specified directory structure.

Constructs a CNN architecture for image classification.

Trains the CNN model using the Adam optimizer and binary cross-entropy loss.

Evaluates the model's performance on a validation set and generates metrics.

Visualizes training and validation accuracy curves.

Provides a function to predict the class (normal or pneumonia) for new images.

## Usage:

Prerequisites: Ensure you have the necessary libraries installed, including TensorFlow, OpenCV, Matplotlib, Pandas, NumPy, and Scikit-learn (optional).

Data Preparation: Organize your chest X-ray images into "NORMAL" and "PNEUMONIA" folders within "train", "test", and "val" subdirectories.

Run the Notebook: Open the Jupyter Notebook file and execute the cells to perform the training, evaluation, and visualization steps.

## Outcomes:

A trained deep learning model for pneumonia classification.

Performance metrics (accuracy, precision, recall, etc.) for the trained model.

Visualizations of training and validation accuracy.

A function to predict pneumonia for new chest X-ray images.

## Additional Notes:

The notebook assumes a specific data directory structure. Adjust paths if your structure differs.

Hyperparameters (e.g., learning rate, number of epochs) can be tuned for better performance.

Consider using transfer learning for potentially better results with limited data.
