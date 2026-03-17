# Breast-Cancer-Detection-Using-CNN-RNN
Project Overview

Breast cancer is one of the most common cancers affecting women worldwide. Early detection significantly improves survival rates.

This project proposes a hybrid deep learning model combining Convolutional Neural Networks (CNN) and Recurrent Neural Networks (RNN) to detect and classify breast cancer stages from mammogram images.

The CNN extracts spatial features from the images, while the RNN captures sequential patterns to improve classification accuracy.

The model classifies images into three stages:

Normal

Beginning Stage

Malignant Stage

Features

Automated breast cancer stage detection

Hybrid CNN + RNN deep learning architecture

Image feature extraction using CNN

Temporal pattern learning using RNN

Improved classification accuracy

Medical image analysis using deep learning

Technologies Used

Python

TensorFlow / Keras

NumPy

Pandas

Matplotlib

OpenCV

Scikit-learn

Jupyter Notebook

Dataset

The dataset consists of mammogram images used for breast cancer diagnosis.

Dataset includes:

Normal images

Early stage cancer images

Malignant cancer images

Images are preprocessed using:

Image resizing

Normalization

Data augmentation

Model Architecture
1. CNN Layer

Used for extracting spatial features from mammogram images.

Typical layers include:

Convolution layers

ReLU activation

Max pooling

Feature maps extraction

2. RNN Layer

Used to learn sequential dependencies from extracted features.

Layers used:

LSTM / RNN layers

Fully connected layers

Softmax classifier

Workflow

Data Collection

Data Preprocessing

Image Feature Extraction using CNN

Sequential Learning using RNN

Model Training

Prediction & Classification

Performance Evaluation

Evaluation Metrics

The model performance is evaluated using:

Accuracy

Precision

Recall

F1 Score

Confusion Matrix

Results

The hybrid CNN–RNN model improves classification performance by combining spatial and temporal feature learning from mammogram images.

The model successfully classifies breast cancer stages with improved detection capability.

Future Improvements

Integration with real-time hospital diagnostic systems

Larger dataset training

Deployment as a web-based diagnostic tool

Integration with explainable AI for medical interpretability

Author

Mudika Siri
B.Tech – Computer Science (Data Science)
Malla Reddy Engineering College for Women

GitHub: https://github.com/siriii29

LinkedIn: www.linkedin.com/in/siri-mudika-5aa3322b7

License

This project is developed for educational and research purposes.

💡 Extra tip (important for GitHub):

Also add these sections if possible:

Installation
git clone https://github.com/your-github-username/your-repo-name
cd your-repo-name
pip install -r requirements.txt
Run the Project
python train_model.py
