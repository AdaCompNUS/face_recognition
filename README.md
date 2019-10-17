The official document is [here](https://github.com/ageitgey/face_recognition). To use this forked repository, follow the below installing guide instead.

## Changes
We have added a face_info python API which will return face_landmarks and face_encodings together in a dictionary for every face in the image.

## Install
Because we modified the face_recognition python library, you should not run ```pip install face_recognition``` anymore. Instead  
1. Install all the requirements
```
pip install face_recognition_models
pip install Click>=6.0
pip install dlib>=19.3.0
pip install numpy
pip install Pillow
pip install scipy>=0.17.0
``` 
2. Git clone this repository

## Use
``` import face_recognition.face_recognition as face_recognition ```




