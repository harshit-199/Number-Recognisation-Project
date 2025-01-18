Welcome to the Handwritten Digit Recognition Model repository! This project demonstrates the development and deployment of a machine learning model designed to recognize handwritten digits (0-9) from images, based on the popular MNIST dataset.

Overview

This project implements a handwritten digit recognition system using Python and machine learning techniques. It leverages the MNIST dataset, which contains 60,000 training images and 10,000 test images. The model achieves high accuracy and serves as an excellent introduction to computer vision and deep learning.

Key Features

Preprocessing of images through normalization and flattening for efficient computation.

Implementation using Python with TensorFlow/Keras, Numpy, Pandas, and other libraries.

Metrics like accuracy, precision, recall, and a confusion matrix for evaluation.

Simple interface for testing the model on custom handwritten digit images.

How to Use

Clone this repository and navigate to the project folder:

git clone https://github.com/yourusername/handwritten-digit-recognition.git
cd handwritten-digit-recognition

Set up the environment and dependencies:

python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
pip install -r requirements.txt

Train the model with the MNIST dataset:

python train_model.py

Evaluate the model's performance:

python evaluate_model.py

Test custom handwritten digit images by placing them in the test_images/ folder and running:

python predict_custom.py --image test_images/your_image.png

Results

Training Accuracy: ~98%

Test Accuracy: ~97%

Contributions

Contributions are welcome! Feel free to fork this repository, create a new branch, and submit a pull request with your enhancements.

License

This project is licensed under the MIT License. See the LICENSE file for details.
