# Real-Time ASL Alphabet Recognizer

A computer vision project that uses a deep learning model to recognize and translate American Sign Language (ASL) alphabet signs from a live webcam feed. This application is designed to demonstrate the practical use of Convolutional Neural Networks for real-time image classification.

---

## Live Demo



---

## Key Features

* **Real-Time Recognition:** Classifies hand signs directly from a live webcam stream.
* **Deep Learning Model:** Built upon the InceptionV3 architecture using the TensorFlow framework.
* **Transfer Learning:** The base model was fine-tuned on a large dataset of ASL alphabet images to achieve specialized recognition.
* **Interactive Interface:** Provides immediate visual feedback by displaying the predicted letter on the screen.

---

## Technologies Used

* **Language:** Python 3.7
* **Core Libraries:**
    * TensorFlow 1.15 (for model training and inference)
    * OpenCV (for video capture and image processing)
    * NumPy
    * Matplotlib

---

## How It Works

The application captures video frames using OpenCV. Each frame is processed and fed into a pre-trained Convolutional Neural Network (CNN), which predicts the corresponding ASL letter. The model was trained using transfer learning, which significantly reduced the training time while maintaining high accuracy.

---

## Acknowledgements

This project was developed by building upon the foundational code from the [original repository by loicmarie](https://github.com/loicmarie/sign-language-alphabet-recognizer).
