![sample](https://raw.githubusercontent.com/lennox0909/Tree_recognition_project/master/img_sample/P_20191010_135321_yolo_leaf.jpg)

# Taiwanese Tree Recognition Project (Aug - Nov, 2019)

As tree lovers, we were aiming for introducing tree's values and benefits to the public. 

* Collecting tree photos among Taiwan mostly in Taipei metropolois.
* Data released on [kaggle](https://www.kaggle.com/c/whichtree-b/data) to encourage attention.
* Trained `YoloV3` to identify trees.
* Build backend on `Google Cloud Platform`
* Build `Line Chatbot` as frontend for user easy access

---

## Target Trees


## Data Collection & Public Released

* 10 members were tree-knowledge trained, then scatter out for photoshooting, where monstly in urban/suburban areas in Taipei.
* Data released on [**kaggle**](https://www.kaggle.com/c/whichtree-b/data) and followed `CC BY 4.0` protocol

## Data Annotation for YOLO training

* [**labelImg**](https://github.com/tzutalin/labelImg) was applied for labeling images before YOLO training

## YOLO Training

* Training process was strongly inspired by [experiencor’s keras-yolo3 project](https://github.com/experiencor/keras-yolo3)
* Revised [**bbox.py**](https://github.com/lennox0909/Tree_recognition_project/blob/master/bbox.py) module to **support truetype fonts and Chinese display**

## Backend Map


## Line Chatbot Frontend Design

* CSS design [folder](https://github.com/lennox0909/Tree_recognition_project/tree/master/line_chatbot/dynamic_reply) for reference

















