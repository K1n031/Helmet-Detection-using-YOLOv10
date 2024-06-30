
# Helmet Detection using YOLOv10

This repository contains code and instructions to train and evaluate a YOLOv10 model for detecting helmets using Google Colab.

## Table of Contents

- Overview
- Setup
- Training the Model
- Validating the Model
- Testing the Model
- Results
- Acknowledgements


## Set up
### Prerequisites
- Google Colab account
### Clone the Repository
```bash
git clone https://github.com/K1n031/Helmet-Detection-using-YOLOv10.git
```
### Install Dependencies
The dependencies are managed within the Colab notebook, so no additional installation steps are required on your local machine. Ensure you run the notebook on Colab for a smooth experience.


## Training the Model
### 1. Open the Notebook:
- Open the 'helmet_detection_using_yolov10.ipynb' file in Google Colab.

### 2. Upload Data:
- Upload your dataset to Google Drive and mount the drive in the Colab notebook.
- Ensure your dataset is structured properly (e.g., with directories for training and testing images).

### 3. Run the Training Cells:
- Follow the instructions within the notebook to configure and start the training process.

## Validate the Model
### 1. Validate on Training Data:
- The notebook contains code to validate the model on the training dataset.
- Ensure the path to the validation data is correctly set in the notebook.
### 2. Evaluate Performance:
- Metrics such as precision, recall, and mAP are calculated to evaluate the model's performance.

## Result
After training and validating, the notebook provides various metrics and visualizations to help understand the model's performance. These include precision, recall, mAP, and visualized predictions on test images.
## Acknowledgements

 - [The official YOLO repository](https://github.com/THU-MIG/yolov10)
 - [Google Colab](https://colab.research.google.com)
