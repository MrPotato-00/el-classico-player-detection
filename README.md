# el-classico-player-detection

## Description
This is the object detection project that uses YOLOv8 to detect football players in an El Clasico football match. The model detects the players as Barcelona and Real Madrid.

## Preprocessing
The preprocessing task involves annotating the images into desired class of objects. I have used roboflow to seamlessly perform the annotation task on the images. The platform provides the option to upload images from the local machine or any youtube url for which it will download the video and divide the video frames into images. The platform provides tool to annotate the images into the desired classes.

## Model Training
For training model I have used the YOLOv8 model to train on the custom data. I have imported the YOLOv8m pretrained model for training, trained over 20 epochs. 

## Prediction
The model predicts the unknown image samples with accuracy ~80%. 
![annoted_el_clasico2](https://github.com/MrPotato-00/el-classico-player-detection/assets/112537239/e046e3f1-17cb-4f01-9060-b25ede720104)

![annoted_el_clasico1](https://github.com/MrPotato-00/el-classico-player-detection/assets/112537239/67157550-ddee-40be-abd8-c1122cfc5c26)

P.S.: The model training metrics will be updated soon.
