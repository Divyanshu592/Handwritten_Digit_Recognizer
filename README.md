## Overview

This project implements a handwritten digit recognition system using a Convolutional Neural Network (CNN) built with Keras and TensorFlow. It achieves high accuracy on the MNIST dataset and supports real-time digit recognition using OpenCV for custom handwritten inputs.

## Features

- **High Accuracy:** Recognition: Achieves over 98% accuracy on the MNIST dataset with an optimized CNN model.

- **Real-Time Digit Detection:** Uses OpenCV for image preprocessing and real-time recognition via webcam or uploaded images.

- **Image Preprocessing:** Normalizes, resizes, and reshapes images to enhance model performance and reduce training time.

- **Custom Digit Prediction:** Recognizes and predicts user-input handwritten digits instantly.

## Setup

To run this application locally, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Divyanshu592/Handwritten-Digit-Recognizer.git
   ```

2. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:

   - **Windows**:

     ```bash
     venv\Scripts\activate
     ```

   - **macOS and Linux**:

     ```bash
     source venv/bin/activate
     ```

4. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Train the Cnn Model:

   ```bash
   python train_model.py

   ```

6. Run the  digit Recognizer:

   ```bash
   python recognize_digit.py

   ```
7. Open your web browser and go to `http://localhost:8000` to access the application.

## Usage

1. Train the model using train_model.py (skip if using pretrained weights).

2. Use recognize_digit.py to detect handwritten digits in real-time via webcam or from images.

3. Customize preprocessing steps in the code to improve accuracy for your specific input style.

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository on GitHub.

2. Create a new branch for your feature or bug fix:

   ```bash
   git checkout -b feature-name
   ```

3. Make your changes and commit them:

   ```bash
   git commit -m "Add new feature"
   ```

4. Push your changes to your forked repository:

   ```bash
   git push origin feature-name
   ```

5. Create a pull request on the original repository.

## Acknowledgments

- Thanks to the MNIST dataset for providing the digit images.

- TensorFlow and Keras for powerful deep learning frameworks.

- OpenCV for real-time image processing capabilities.
  
Feel free to customize and enhance this expense tracker according to your needs. Happy budgeting!
