# Steganography using AI with python
This project uses AI-powered steganography, where a VGG16 model selects the best image for embedding a secret message. Built with Python, OpenCV, NumPy, and TensorFlow, it ensures secure message hiding and extraction.
# Features

**AI-Based Image Selection:**
* Uses a VGG16 deep learning model to analyse and selects the best image for steganography.

**Secure Message Embedding:**
* Hides text messages within the image.

**Loseless Extraction:**
* Ensures accurate retrieval of hidden messages.

**Supports Multiple Image Formats:**
* Works with .png,.jpg,and more.

**Python Based Implementation:**
* Built using TenserFlow,OpenCV,and NumPy for efficient processing.

# Requirements
- Python 3.x

- Jupyter Notebook

- TensorFlow

- OpenCV

- NumPy 

- Scikit Image

 # How It Works

* This project utilizes AI-based image selection and steganography techniques to hide messages inside images securely. Below is an overview of the working process:

🔹-**Step 1:** Image Selection Using AI

* The program scans all images in the images/ folder.

* It uses a pre-trained deep learning model (VGG16) to analyze image features.

* The AI selects the most suitable image for steganography based on extracted features.


🔹 -**Step 2:** Message Encryption into Image

* The selected image is processed to embed a secret message inside its pixel data.

* The message is encrypted to enhance security.

* The modified image is saved for later retrieval.


🔹 -**Step 3:** Message Extraction (Decryption)

* The recipient loads the encrypted image.

* The program extracts and decrypts the hidden message from the image.


* This approach ensures secure and intelligent data hiding while leveraging AI for optimized image selection.

  


