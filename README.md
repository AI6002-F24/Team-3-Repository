# Team-3-Repository

## Progress_YOLOv7_Train

This file contains the code to build the YOLO v7 model and obtain the best trained model on the basis of the dataset fed.

## Capstone_Testing_After_Training

This file contains the code to use the best weights obtained after training the YOLO model and generate predictions on any dataset as desired. The Regions of Interest are marked as per the prediction and can also be visualized.

## Bulk_cheque_rename

This utility file helps to correct the names of the annotated images and labels obtained from Roboflow since they are not in the proper order. It also helps to extract each section of the predicted part of the image by each section.

## YOLO_V8_Training_Final

This file contains all the code required to train the final YOLO v8 nano model we will be using for our Cheque Image object detection.
Around 400 epochs is required to give good results which may need to be increased with variegated dataset.

## custom_8parts.yaml

Custom YAML file that needs to be uploaded for the model to label the objects it finds accordingly.

## YOLOv8_Inference

This file helps to draw inference from images provided and store the extracted part of the images as separate images so that they could be used in the next step of the fraud detection process.
