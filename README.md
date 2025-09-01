# Assignment_5
This project applies deep learning techniques to detect Tuberculosis from chest X-ray images. It uses convolutional neural networks (CNNs) for automated feature extraction and classification. The model aims to support early diagnosis and assist healthcare professionals in decision-making.

🩺 Tuberculosis Detection Using Deep Learning
📌 Project Overview

This project applies deep learning techniques to detect Tuberculosis (TB) from chest X-ray images.
A Convolutional Neural Network (CNN) is trained to automatically extract features and classify X-rays as Normal or TB-infected, aiming to support early diagnosis and assist healthcare professionals.

⚙️ Requirements
Make sure you have the following installed:
Python 3.8+
TensorFlow / Keras
NumPy
Pandas
Matplotlib
scikit-learn

Install all dependencies:
pip install -r requirements.txt

📂 Dataset
The dataset consists of Normal and TB-infected chest X-ray images.
You can use publicly available datasets such as Tuberculosis Chest X-ray Dataset
 or your own dataset.

Place the dataset inside a folder structure like this:
Dataset/
 ├── Normal/
 └── TB/

🚀 Usage
Run the Jupyter Notebook:
jupyter notebook "TB detection using DL.ipynb"
Or run as a Python script:
python train_model.py

📊 Results
The model achieves high accuracy in detecting TB.
Performance metrics include Accuracy, Precision, Recall, and F1-score.
Confusion matrix and training graphs are included in the notebook.

📌 Future Work

Improve model performance with advanced architectures (ResNet, EfficientNet).
Deploy as a web or mobile application for real-time TB detection.
Enhance dataset size and diversity for better generalization.
