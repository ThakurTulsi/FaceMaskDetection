# Face Mask Detection Project

This project focuses on developing a Face Mask Detection system using Python and OpenCV. The program utilizes computer vision techniques to identify faces and determine whether individuals are wearing masks.

## Installation

Make sure to install the required libraries using the following command:

```bash
pip install opencv-python
```

## Usage

1. Run the initial code to display an image with OpenCV.
2. Explore the face detection capabilities by drawing rectangles around detected faces.
3. Extend the project by capturing data for training the model. The captured images are saved separately for individuals with and without masks.

## Files

- `face_mask_detection.ipynb`: Jupyter Notebook containing the code.
- `without_mask.npy`: NumPy file containing images of faces without masks.
- `with_mask.npy`: NumPy file containing images of faces with masks.

## Face Detection

The project employs the Haar Cascade Classifier for face detection, outlining faces with rectangles. The data collection phase involves capturing facial images to train a machine learning model for mask detection.

## Data Collection

1. Execute the code for data collection by running the specified command.
2. Press the 'Escape' key to exit the data collection phase or when a sufficient number of images have been captured.

## Data Storage

The captured facial images are stored in separate NumPy files for individuals with and without masks:

- `without_mask.npy`: Images of faces without masks.
- `with_mask.npy`: Images of faces with masks.

## Note

Ensure that your environment has a webcam connected and properly configured for face detection and data collection.

Feel free to experiment and enhance the project for real-time mask detection applications!
