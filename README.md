AI-Vision in Healthcare
====================================

## Overview
This project aims to employ yolov8 model, for image classification on skin carcinoma, for the purpose of distinguishing b/w Carcinoma stages , thus serving as a useful tool in medical diagnosis.
* Yolov8 model was trained on medical imaging data , so that it can classify b/w Melanoma and Basal Cell Carcinoma states. Dataset was loaded from robflow
* Two natural images were obtained on which annotation was performed (edge detection,scaling, noising/denoising etc) to make them ready for training purpose
* Ideas about computer vision and how image processing enables creation of suitable dataset for the purpose of training were explored.

## Resources

Colab notebook -https://colab.research.google.com/github/roboflow-ai/notebooks/blob/main/notebooks/train-yolov8-classification-on-custom-dataset.ipynb#scrollTo=Wjc1ctZykYuf

Dataset was obtained from robflow - it had two classes -Basal cell carcinoma and Melanoma
https://universe.roboflow.com/cxrdataset/skin-ga5ww

## How to run Yolov8 for tarining
* Any dataset can be obtained with atleast two classes from either robflow/Mnist in zip format.
* Available GPU can be used provided freely by google for training model. Select Edit> notebook settings> T4GPU >save for successfully connecting to GPU environment.
* !pip install ultarlytic. For detailed command on installation refer to colab robflow notebook.
* Copy paste the data.zip file on folder section > unzip the data.
* Run the yolo model
* Predict the images for ensuring the model has run correctly .Check for the correct path of best.pt file while running prediction on images.

## Future Directions
The project can be extended from a simple prediction model to dispalying labels and the accuracy of results.
