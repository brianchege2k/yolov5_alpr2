## INTRODUCTION

This is the README File for the Automatic License Plate Recognition Model Using Convolutional Neural Network (CNN) - YOLOv5. Please do consider reading it fully.

## Files in the Repository
1. images folder - Images to be to do inferencing on the model and make predictions
2. yolov5 folder - Folder containing the trained YOLOv5 model, dependencies, requirements, relevant diagrams from training etc
3. README.md file - Markdown file explaining in detail how to use successfully the model
4. YOLOv5_ALPR_PROJECT.ipynb - Jupyter Source file on how the model was trained
5. inferencing.ipynb - Jupyter source file that can be used to do predictions using trained model
6. requirements.txt - All requirements that are needed by the model before it can be used (YOU MUST INSTALL THESE BEFORE STARTING THE TEST AS THE MODEL WILL NOT RUN)


## DATASET 
The Model is trained on a total of 1168 images and Validated on a total of 297 images on the Google Colab platform [Google Colab Platform](https:colab.research.google.com)
These images are all accessed from my Google Drive folder [Drive Folder](https://drive.google.com/drive/folders/1CAR-syFis4CWqi04dXV852o0LBgfnWbp?usp=sharing) Note: The files with a .txt extensions were obtained by converting annotation files that are in .xml format to a format suitable for training a YOLO model.



## Instructions on how to run the trained model

## NB: To run make sure you have Python installed in your machine and that python is present in your environment variables. You can check if python is present by searching 'environment variables' on the search bar or pressing Windows + R and running this command 'sysdm.cpl', head to Advanced Tab and click on Environment variables, Under the PATH variable you should see the path to the executable python version that is installed in your machine.

## If you dont have Python, follow this link to get a python version of (Reccommended 3.8 and above)
[Python Download](https://www.python.org/downloads/) 
## While installing make sure you check the "ADD TO PATH checkbox" and also check the 'Disable PATH Length Limit checkbox'


## STEPS TO RUN THE MODEL

1. Clone or download this repository to your directory of liking
2. Open the folder in a code editor (VS code reccommended) or another suitable IDE plaform
3. Install neccessary requirements using the following command on your terminal using this command `pip install -r .\requirements.txt`
4. Use the jupyter source file named 'inferencing.ipynb' and execute respective cells to carry out testing
 
## The Output will provide an image with an a bounding box , Object detection confidence score, and character recognition results also an output of more detailed bounding box co-ordinates and both the object detection and OCR onfidence score as a floating point number example;

## EXAMPLE RESULTS 

Object Detection Results:
Object 1:
  Class: license_plate
  Confidence: 0.9223561882972717
  Bounding Box: [340, 739, 704, 831]
  OCR Results:
    OCR 1: ([[2, 10], [356, 10], [356, 86], [2, 86]], 'KDJ. 542R', 0.9494196080888768)



## THANK YOU FOR DOWNLOADING!