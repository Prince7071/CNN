# Digits Recognition Neural Network

A deep learning project that classifies handwritten digits from the MNIST dataset using a Convolutional Neural Network (CNN) built with TensorFlow and Keras. This model achieves high accuracy and is capable of predicting digits from both the test set and custom input images.

Features
CNN-based architecture for image classification

Trained on the MNIST dataset (70,000 28×28 grayscale images)

Visualizations of training process and results

Real-time prediction on custom input images

Model saving/loading using model.save() and load_model()

🧾 Project Structure
bash
Copy
Edit
digits_recognition_neural_network/
│
├── digits_recognition.ipynb      # Jupyter notebook with full code
├── model/                        # Folder to store saved CNN model
│   └── digits_cnn_model.h5
├── test_images/                  # Folder for custom test images
│   └── sample_digit.png
├── README.md                     # Project documentation
└── requirements.txt              # Python dependencies
🧪 Dataset
This project uses the MNIST dataset, available directly through Keras:

python
Copy
Edit
from tensorflow.keras.datasets import mnist
60,000 training images

10,000 testing images

Image size: 28×28 pixels, grayscale

Labels: 0 to 9
