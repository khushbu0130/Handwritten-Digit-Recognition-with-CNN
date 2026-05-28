# Handwritten Digit Recognizer using Deep Learning

A Python-based handwritten digit recognition system that uses a Convolutional Neural Network (CNN) trained on the MNIST dataset to accurately classify handwritten digits.

## Features

- Handwritten digit recognition using CNN
- GUI drawing canvas built with Tkinter
- Real-time digit prediction
- Deep learning model trained on MNIST dataset
- Image preprocessing and normalization
- Model saving using Keras

---

## Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Tkinter
- PIL (Pillow)

---

## Project Structure

```bash
├── gui_digit_recognizer.py
├── train_digit_recognizer.py
├── mnist.h5
└── README.md
```

---

## Model Architecture

The CNN model consists of:

- Conv2D Layer
- MaxPooling2D
- Flatten Layer
- Dense Layers
- Dropout Layers
- Softmax Output Layer

Implemented using Keras Sequential API. :contentReference[oaicite:0]{index=0}

---

## How It Works

1. Train the model using the MNIST dataset
2. Save the trained model as `mnist.h5`
3. Launch the GUI application
4. Draw a digit on the canvas
5. Click on "Recognise"
6. The model predicts the digit with confidence score

GUI implementation uses Tkinter canvas drawing and image preprocessing. :contentReference[oaicite:1]{index=1}

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/mnist-digit-recognizer.git
cd mnist-digit-recognizer
```

### Install Dependencies

```bash
pip install tensorflow keras pillow numpy pywin32
```

---

## Run the Project

### Train the Model

```bash
python train_digit_recognizer.py
```

### Run GUI Application

```bash
python gui_digit_recognizer.py
```

---

## Output

### Training Output

```bash
The model has successfully trained
Test accuracy: 98%
Saving the model as mnist.h5
```

### GUI Prediction Output

```bash
Prediction: 7, 99%
```

---

## Future Improvements

- Improve GUI design
- Add support for custom datasets
- Deploy as a web application
- Add real-time drawing smoothing
- Improve prediction accuracy

---

## Author

Khushbu Kumari
