# Sign Language Interpreter

A **Python-based Sign Language Interpreter** that translates hand gestures into text in real-time using computer vision and machine learning. This project helps bridge the communication gap for individuals who use sign language.

## Features

- Real-time gesture recognition using a webcam
- Displays recognized gestu

## Installation

**Clone the repository**  
```bash
git https://github.com/amirtak0685/SignLanguageDetector.git
cd SignLanguageDetector
```
## How to run

Follow the steps outlined in Tutorial.ipynb to run the program

## Dependencies

This project requires the following Python packages:

- **Python 3.8+**
- **OpenCV** (`opencv-python`) – For computer vision and webcam input
- **Mediapipe** (`mediapipe`) – For hand landmark detection
- **NumPy** (`numpy`) – For numerical operations
- **TensorFlow** (`tensorflow`) or **PyTorch** (`torch`) – Depending on the trained model used

### Installing Dependencies

You can install all dependencies using `pip`:

```bash
pip install opencv-python mediapipe numpy tensorflow
# or, if using PyTorch
pip install opencv-python mediapipe numpy torch
