# Object Recognition Project

:computer: Image Recognition: Nuts and Screws

This repository presents a project focused on image recognition of nuts and screws using object detection techniques. The objective is to develop a model capable of accurately detecting and classifying nuts and screws in images, enabling automation and quality control in industrial settings.

## :wrench: Overview

The project consists of the following stages:

1. :computer: Import Dependencies: Installation of necessary dependencies, including OpenCV, UUID, and others.
2. :computer: Define Images to Collect: Setting the labels (nuts and screws) and the number of images to collect for each label.
3. :computer: Setup Folders: Creating the necessary folder structure for storing collected images.
4. :computer: Capture Images: Utilizing the webcam to capture a specified number of images for each label.
5. :computer: Image Labelling: Using the LabelImg tool to annotate and label the collected images.
6. :computer: Move them into a Training and Testing Partition: Organizing the labelled images into separate training and testing sets.
7. :computer: Compress them for Colab Training (Optional): Compressing the image data for training on Colab.

## :gear: Technologies Used

The project leverages the following technologies:

- Python
- OpenCV
- LabelImg

These technologies are used for image capture, labelling, and dataset preparation.

## :rocket: Getting Started

To run the project locally, follow these steps:

1. Install the necessary dependencies by running `pip install -r requirements.txt`.
2. Run the Jupyter notebook file to capture images, perform labelling, and prepare the dataset.

## :file_folder: Project Structure

The project has the following file structure:
```
├── images
│ ├── collectedimages
│ │ ├── screw
│ │ └── nut
│ ├── train
│ └── test
├── Tensorflow
│ ├── labelimg
│ │ ├── labelImg.py
│ │ ├── libs
│ │ └── resources.qrc
│ └── workspace
│ ├── annotations
│ ├── images
│ └── models
├── generate_tfrecord.py
└── README.md
```

- `images/collectedimages`: Folder for storing the collected images of nuts and screws.
- `images/train`: Folder for training images.
- `images/test`: Folder for testing images.
- `Tensorflow/labelimg`: Directory containing the LabelImg tool for image labelling.
- `Tensorflow/workspace`: Workspace directory for TensorFlow object detection.
- `generate_tfrecord.py`: Python script to generate TFRecord files for training and testing.

## :chart_with_upwards_trend: Results and Evaluation

The trained model can be evaluated by running the provided Jupyter notebook, which includes the image recognition code. The notebook loads the trained model, processes the test images, and displays the detection results.

## :raising_hand: Contributing

Contributions to this project are welcome. If you have any suggestions, please open an issue or submit a pull request.

## :page_facing_up: License

This project is licensed under the MIT License. You are free to use, modify, and distribute the code for educational or commercial purposes.

## :email: Contact

For any questions or inquiries, please contact at jair2000.0224@hotmail.com.
