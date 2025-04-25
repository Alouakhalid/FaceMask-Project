🧠 Face Mask Detection using Custom CNN
This project is part of my internship at Uneeq Interns, where I built a deep learning model from scratch to detect whether a person is wearing a mask or not.

📌 Overview
The goal of this project is to classify images of human faces into two categories:

With Mask

Without Mask

This classification task is performed using a custom Convolutional Neural Network (CNN) developed in TensorFlow/Keras.

🧰 Tech Stack
Python

TensorFlow & Keras

NumPy

PIL (Python Imaging Library)

scikit-learn

Matplotlib

📁 Dataset
The dataset used for training and testing is publicly available on Kaggle:

🔗 Kaggle Dataset: Face Mask Detection Dataset

It contains:

with_mask: Images of faces wearing masks

without_mask: Images of faces not wearing masks

Each image is resized to 128x128 and converted to RGB format before training.

🔧 How It Works
Data Loading & Preprocessing

Images are loaded and converted into arrays.

Dataset is labeled and split into training and testing sets.

Model Architecture
Custom CNN using:

Conv2D + MaxPooling

Dropout for regularization

Dense layers for binary classification

Training

Loss: Binary Cross-Entropy

Optimizer: Adam

Evaluation Metric: Accuracy

Training logs saved using CSVLogger

Evaluation & Visualization

Plotted accuracy and loss over epochs

Tested on unseen data for performance validation

📈 Results
High accuracy on test data

Efficient and lightweight CNN model suitable for basic face mask detection tasks

▶️ How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/face-mask-detection.git
cd face-mask-detection
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook: Open Face Mask.ipynb in Jupyter Notebook or Colab and run all cells.

🙌 Acknowledgements
Thanks to Uneeq Interns for the opportunity and mentorship.
Dataset by Ashish Jangra on Kaggle.

