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

## GUI_Streamlit

This file contains the code for running a Streamlit webapp on the Streamlit community server after going through a tunnel. It is fully functional and runs the YOLO v8 nano model in the backend to predict cheque fields and display them. This only has the problem that it crashes very often since the community on Streamlit is very active. Only use the block of the notebook from the Final Trial section.


## Flask_App.zip

This is the zipped folder that has all the required codefiles in the proper structure to run a webapp locally using flask and run the demo version of our application.

## Flask App structure
![image_2024-11-24_091520448](https://github.com/user-attachments/assets/06fc3c00-0133-43c9-bb45-4197a50c0e4a)

## Sign_Verification

This file contains the code for building and training a Siamese Network for verifying signatures. The network detects how similar each sign is to each other and associates a distance between them which in turn can be used as a threshold to distinguish between real and forged signatures.

## Signature Verification Dataset

The folders are too large to upload on Github so sharing the drive links here -
* Train Data - <https://drive.google.com/drive/folders/1T26e3YW4h3flzvNstv1XBA7WG_crOu4m?usp=drive_link>
* Test Data - <https://drive.google.com/drive/folders/17Rc7wARbWsGc5UrYRA83PMRdUAObsq9u?usp=drive_link>
* Train metadata - <https://drive.google.com/file/d/1n1zAkelM7eCMtZe9f-W1bZJHUEWqTubV/view?usp=drive_link>
* Test metadata - <https://drive.google.com/file/d/1Xyedk2bld7IJqi6ZQevXn91-hgaDtEmI/view?usp=drive_link>

## User Setup and Usage
This file contains the detailed information on how to setup and use the system on any machine. The required steps are highlighted with visual aids which makes setting up and using the system an easy task.



## Contributors

* Sanjana Khan Shammi (202294234)
* Chiradip Bhattacharya (202292781)
* Rohit Arora (202292817)

## License

MIT License

