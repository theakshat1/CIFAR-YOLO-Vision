# CIFAR-YOLO-Vision
This repository contains code for image classification using a Convolutional Neural Network (CNN) on the CIFAR-10 dataset, as well as object detection using the YOLO (You Only Look Once) algorithm.

The object detection model is built using TensorFlow and Keras, while the YOLO algorithm is implemented using OpenCV and Darknet. The repository provides a comprehensive example of how to train a CNN for image classification and perform object detection on images. The code includes data preprocessing, model training, and visualization of results. It serves as a practical guide for understanding and implementing these computer vision techniques.

## Image Classification

The code includes the following steps for image classification:

1. Loading and preprocessing the CIFAR-10 dataset.
2. Building a CNN model for image classification.
3. Training the model on the dataset.
4. Evaluating the model's performance on test data.

## Object Detection

The code also demonstrates object detection using the YOLO algorithm:

1. Downloading the YOLO model files and class names.
2. Loading the YOLO model and class labels.
3. Downloading a test image and running object detection on it.
4. Displaying the image with bounding boxes and labels for detected objects.

## Usage

To use the code in this repository, follow these steps:

1. Install the required dependencies: TensorFlow, Keras, OpenCV.
2. Clone the repository: `git clone https://github.com/theakshat1/CIFAR-YOLO-Vision`
3. Navigate to the repository directory: `cd CIFAR-YOLO-Vision`
4. Install the required dependencies using pip: `pip install -U -r requirements.txt`

Modify `YOLOv3.ipynb` to your system.
(Project made on Google Colab)

## Resources

- [CIFAR-10 Dataset](https://www.cs.toronto.edu/~kriz/cifar.html)
- [YOLO (You Only Look Once) Algorithm](https://pjreddie.com/darknet/yolo/)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
