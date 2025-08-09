# Brain-tumor-detection-using-CNN
This project is about detecting brain tumors from MRI images using a Convolutional Neural Network (CNN).
The model classifies images into tumor and no-tumor categories with good accuracy.

Dataset
Dataset taken from Kaggle (Brain MRI dataset)

Contains images of brain with tumor and without tumor

Stored in a ZIP file — needs to be extracted before running the code

Tools & Libraries Used
Python

TensorFlow / Keras

NumPy

Pandas

OpenCV

Matplotlib

scikit-learn

Steps in the Project
Data Preprocessing

Load and resize images

Normalize pixel values

Split into training and testing sets

Model Building

CNN architecture using Keras

Activation: ReLU

Output Layer: Sigmoid

Model Training

Adam optimizer

Binary cross-entropy loss

Track accuracy and loss

Evaluation

Accuracy score

Loss curves

Confusion matrix

Prediction

Test the model with new MRI images

Output prediction as tumor / no-tumor

How to Run
Extract the dataset ZIP file.

Update the dataset path in the notebook.

Run all cells in brain tumor detection.ipyng.ipynb.

Check the output accuracy and prediction results.

Output
Training and validation accuracy

Loss curves

Confusion matrix

Prediction result for new image


