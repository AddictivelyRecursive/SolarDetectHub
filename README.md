
# SolarDetectHub
SolarDetectHub is a project focused on detecting solar panels in satellite images using YOLO (You Only Look Once) models and COCO (Common Objects in Context) annotations. The goal is to accurately identify and locate solar panels in staellite imagery.

# Overview
This project utilizes YOLO models, known for their real-time object detection capabilities, to perform semantic segmentation on satellite images. By training the model on annotated datasets, SolarDetectHub aims to predict the presence and location of solar panels for every pixel in the input image.

# Usage
The main modules in this project include:

datasetStatistics.ipynb: Analyzes and summarizes characteristics of number of Solar Panels.

modelYOLO.ipynb: Handles the training and evaluation of the YOLO model.

modelEvaluation.ipynb: Contains scripts for evaluating model performance.

averagePrecision.ipynb: Calculates the average precision of the model.

modelVisualResults.ipynb: Visualizes the detection results.


# Dataset
The dataset used for training and evaluation consists of satellite images with corresponding COCO-style annotations. The images are stored in the image_chips_native directory, and the annotations are in the labels_native directory.

# Visualization
To visualize the detection results, use the modelVisualResults.ipynb notebook. This will generate images with bounding boxes around detected solar panels, allowing for qualitative assessment of the model's performance.
