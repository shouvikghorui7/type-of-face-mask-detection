# Facial Mask Detection using CNN ResNet-2

![Facial Mask Detection](demo.gif)

This repository contains code for building a Convolutional Neural Network (CNN) based on the ResNet version 2 architecture to detect facial masks in images and real-time videos. The model is trained on a dataset containing various types of face masks, including cloth masks, N95 masks, N95 masks with valves, surgical masks, and images without face masks.

## Dataset

The dataset used for training and evaluation can be found on Kaggle: [Face Mask Types Dataset](https://www.kaggle.com/example/face-mask-types-dataset). It contains images categorized into the following classes:

- `cloth`: Cloth face mask images
- `n95`: N95 face mask images
- `n95v`: N95 with Valve face mask images
- `nfm`: No Face Mask images
- `srg`: Surgical face mask images

The train and test sets are already separated in the dataset.

## Requirements

- Python 3.x
- TensorFlow 
- OpenCV
- NumPy 
- Matplotlib 

You can install the required packages using pip:


pip install tensorflow opencv-python numpy matplotlib

## Demo Video

[![Facial Mask Detection Demo](example.com/demo_video_thumbnail.jpg)](example.com/demo_video.mp4)

Replace `example.com/demo_video_thumbnail.jpg` with the URL to your demo video thumbnail image, and `example.com/demo_video.mp4` with the URL to your demo video. This video showcases the facial mask detection model in action, displaying bounding boxes and class labels for face masks in real-time.


