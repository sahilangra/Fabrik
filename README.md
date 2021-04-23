# Fabrik

Hi, This project trains a MobileNetV2 using Tensorflow Object Detection API and is run into the browser via Tensorflow.js

Steps followed while creating the project:

1. The data is first collected and passed through LabelImg. Here we capture the connector and its annotations are obtained in .XML format.
2. The .XML format data is merged converted into a single .csv file
3. The MobileNetV2 model is downloaded, its weights are used as initial weights.
4. Training and validation of model takes place.
5. The model is saved.
6. tensorflowjs_wizard is used for conversion to tensorflow.js layer format
7. The model is called via the website
