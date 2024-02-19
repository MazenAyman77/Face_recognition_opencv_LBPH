# Face Recognition With Open-CV

## Description
we use OpenCV library with python to recognize faces and take an action according to the face is known or not.

## Requirements 
* Python 2.7
* OpenCV 3.4
* Numpy

## How To Run
1. Create two folders **dataset** and **recognizer** beside the source code
2. Run **dataset_creator.py** script to take photos of the face and store it in **dataset** folder
    - Enter the name of the user which will be stored
    - Enter an id for him
3. Run **trainer.py** script to extract data from dataset and store it in **recognizer/training_data.yml**
4. Run **face_recognition.py** script that will detect the face and put the name under it
