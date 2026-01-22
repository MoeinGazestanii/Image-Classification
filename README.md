# Celebrity Image Classification
This project is a machine learning pipeline designed to classify images of celebrities. It utilizes computer vision techniques for image processing and machine learning algorithms to identify specific personalities from input images.

## Project Overview
The goal of this project is to build an automated system capable of recognizing faces and classifying them into specific categories (celebrities). The workflow includes loading images, preprocessing them using OpenCV, training a classifier using Scikit-Learn, and saving the model for deployment.

## Tools Used
Python
OpenCV (cv2) (Image processing and loading)
Matplotlib & Seaborn (Data visualization)
NumPy & Pandas (Data manipulation)
Scikit-Learn (Model training, evaluation, and GridSearch)
Joblib (Model serialization)

## Dataset
The model is trained to recognize specific celebrities. Based on the code, the classes include:
Elon Musk
Lionel Messi
Oprah Winfrey
Warren Buffett

## Key Steps
### Data Preprocessing
Image Loading: Images are loaded using OpenCV.
Visualization: The notebook includes steps to display images using Matplotlib to verify data integrity.
Feature Extraction: The raw image data is likely processed (e.g., flattened or cropped) to be suitable for the machine learning model.

### Model Training
The project trains a classifier (referenced as best_clf in the code).
It employs techniques like GridSearchCV to tune hyperparameters and find the most accurate model.

### Model Evaluation
The performance of the model is analyzed using standard metrics (likely Confusion Matrix or Classification Reports).
Visualizations are used to understand how well the model separates the different classes.

### Model Export
The trained model is saved using joblib as saved_model.pkl.
A class dictionary is also generated (e.g., {'elon musk': 0, 'lionel messi': 1...}) to map numerical predictions back to celebrity names.
---
**Author:** Moein Gazestani
