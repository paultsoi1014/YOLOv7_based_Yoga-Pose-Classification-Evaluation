# Yoga Pose Classification and Evaluation
* Using YOLO-based model to achieve yoga pose classification 
* Movenet is adopted for yoga pose evaluation

## Project workflow
1. YOLOv7 custom model (YOLOv7_Custom_training.ipynb) was created based on yoga pose dataset from kaggle [link text](https://www.kaggle.com/datasets/niharika41298/yoga-poses-dataset)
* Labelling was done using Roboflow
![](https://drive.google.com/uc?export=view&id=1Z9D9aoqciDhjJaAB-_uRU8MsFgQl1CLs)


### Sample output
![](https://drive.google.com/uc?export=view&id=1xOnYO71Jk8NxO9uXLudqP33Ux0HEnH_E)

![](https://drive.google.com/uc?export=view&id=1yM1zoBJK2ahXr7Urq1l7wabNkRcywoYz)

2. The trained weight (best.pt) and modified .py file for detection (detect.py) are stored in the yolov7_custom folder


