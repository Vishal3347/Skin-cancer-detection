# Skin Cancer Detection using CNN  

A deep learning-based system for automated detection and classification of skin cancer lesions using Convolutional Neural Networks (CNNs). Achieves 95% validation accuracy in distinguishing between malignant and benign skin lesions.

📊 Project Overview
This project implements a CNN-based image classification system designed to assist in early detection of skin cancer. The model was trained on the ISIC/HAM10000 dataset containing over 5,000 dermatoscopic images.

✨ Key Features
High Accuracy: ~95% validation accuracy on test data

Transfer Learning: Leveraged pre-trained models for improved performance

Data Augmentation: Enhanced generalization with image transformations

Reproducible Pipelines: Consistent training and evaluation workflows

Hyperparameter Tuning: Systematic optimization for model performance

🛠️ Technologies Used
Python 3.8+

TensorFlow/Keras - Deep learning framework

OpenCV - Image processing and augmentation

NumPy & Pandas - Data manipulation

Matplotlib/Seaborn - Visualization

Jupyter Notebook - Experimentation and analysis

📁 Dataset
The model was trained on the HAM10000 dataset from the International Skin Imaging Collaboration (ISIC), containing:

5,000+ dermatoscopic images

7 different classes of skin lesions

Balanced representation of malignant vs. benign cases

Download: HAM10000 on Kaggle

🚀 Installation & Setup
Prerequisites
Python 3.8 or higher

pip package manager

Installation Steps
Clone the repository


Create virtual environment

bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
Install dependencies



#  use the Jupyter notebook
jupyter notebook Untitled0.ipynb
Training Parameters
Optimizer: Adam

Loss Function: Categorical Crossentropy

Epochs: 50-100 (with early stopping)

Batch Size: 32

Validation Split: 20%

Data Augmentation Techniques
Random rotation (±30°)

Horizontal/Vertical flipping

Brightness/Contrast adjustment

Zoom and shear transformations

📊 Results

Metric	Value

Validation Accuracy	~95%

Precision	94.2%

Recall	95.1%

F1-Score	94.6%
