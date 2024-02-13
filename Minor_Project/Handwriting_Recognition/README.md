## Handwriting Recognition Project 
This project aims to develop a handwriting recognition system using convolutional neural networks (CNNs) and machine learning techniques. The system can recognize handwritten digits from the MNIST dataset and provide accurate predictions.

### Table of Contents 
* Introduction
* Features
* Requirements
* Installation
* Usage
* Model Architecture
* Training
* Evaluation

### Introduction
Handwriting recognition is the ability of a computer to interpret and recognize human handwriting. This project focuses on recognizing handwritten digits, which is a fundamental problem in the field of pattern recognition and computer vision.

### Features
1. Recognizes handwritten digits (0-9) accurately.
2. Utilizes CNNs for feature extraction and classification.
3. Implements data augmentation techniques for improved model generalization.
4. Provides evaluation metrics such as accuracy for model performance assessment.

### Requirements
To run this project, you need:

[Python](https://www.python.org/downloads/)

[TensorFlow (>=2.0)](https://pypi.org/project/tensorflow/)

[Numpy](https://numpy.org/install/)

[Matplotlib](https://matplotlib.org/)

### Installation
Clone the repository and Install the required Python packages:
```
git clone https://github.com/Lajvi123/CODESTRING.git
cd CODESTRING/Minor_Project/Handwriting_Recognition
pip install -r requirements.txt
```
### Usage 
Open the notebook file Handwriting Recognition.ipynb in Jupyter Notebook or JupyterLab:
```
jupyter notebook notebook.ipynb
```
### Methodology 
1. Data Acquisition : The project uses the MNIST dataset, which consists of 60,000 training images and 10,000 testing images of handwritten digits (0-9).
  
2. Data Augmentation : Data augmentation techniques are applied to increase the variability of the training data and improve the model's ability to generalize to unseen data.
- Techniques such as rotation, shifting, shearing, zooming, and flipping are applied to the training images using the `ImageDataGenerator` class from TensorFlow/Keras.
  
3. Model Architecture
The architecture is designed to effectively capture and learn the patterns present in handwritten digits.
<img width="597" alt="Screenshot 2024-02-13 at 4 20 24 PM" src="https://github.com/Lajvi123/CODESTRING/assets/142981262/2816e84b-6d51-4acf-8c8e-8b5922911693">

4. Training : Training is performed using the Adam optimizer with a categorical cross-entropy loss function.

5. Evaluation : After training, the model's performance is evaluated using the original (non-augmented) testing data.

   
