# Image-Classification-Model
A simple image classification model trained with Teachable Machine and tested on Google Colab, using a pre-trained Keras model to classify images (e.g., cats and dogs) with confidence scores.

Image Classification Model
Overview

This project utilizes a pre-trained Keras model to classify images into different categories (e.g., cats and dogs). The model was trained using Teachable Machine and tested on Google Colab for inference.
Requirements
Python 3.x
TensorFlow
Pillow (PIL)
NumPy

Install the required packages using:
pip install tensorflow pillow numpy

Files

keras_model.h5: The pre-trained model file, exported from Teachable Machine.
labels.txt: File containing class names.
test.jpg: Sample image for testing.
sample_data/: Directory containing additional sample data.

Pictures

![Uploading image.png…]()

![لقطة شاشة 2025-06-30 230350](https://github.com/user-attachments/assets/80dc00b9-696b-4b3e-a6b4-e2740b9ab0c7)

![لقطة شاشة 2025-06-30 233757](https://github.com/user-attachments/assets/ee6fab6b-17cc-4a27-9f86-f064787d3330)

![لقطة شاشة 2025-06-30 233742](https://github.com/user-attachments/assets/3cfa1edd-903c-40ba-aed3-e6a3ce389a10)

Usage

Ensure all required packages are installed.
Upload the keras_model.h5, labels.txt, and test.jpg files to your Google Colab environment.
Run the provided script in Google Colab to classify the image and get the prediction along with the confidence score.
Update the image = Image.open("test.jpg") line with the path to your image if different.

Script Explanation

The script loads the pre-trained model and labels.
It processes the input image by resizing and normalizing it.
The model predicts the class and confidence score, which are then printed.

Example Output
Class: Dogs
Confidence Score: 0.9998236

Workflow

Training: The model was trained using Teachable Machine (https://teachablemachine.withgoogle.com/).
Testing: Inference was performed using Google Colab (https://colab.research.google.com/).



Contributing
Feel free to fork this repository and submit pull requests for improvements.
License
This project is licensed under the MIT License.
