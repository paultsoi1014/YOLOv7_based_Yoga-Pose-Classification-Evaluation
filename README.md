# Yoga Pose Classification and Evaluation
* Using YOLO-based model to achieve yoga pose classification (Tree & Godness)
* Achieve human pose detection through using MoveNet lightning 

## Project workflow
### Step 1
Train a custom object detection model with YOLO v7 (YOLOv7_Custom_training.ipynb) [link text](https://github.com/WongKinYiu/yolov7)

* Training data was collected from yoga pose dataset [link text](https://www.kaggle.com/datasets/niharika41298/yoga-poses-dataset)
* Labelling was done using Roboflow
![](https://drive.google.com/uc?export=view&id=1Z9D9aoqciDhjJaAB-_uRU8MsFgQl1CLs)

#### For further details, please browse the YOLOv7_Custom_training.ipynb file
### Sample output
![](https://drive.google.com/uc?export=view&id=1xOnYO71Jk8NxO9uXLudqP33Ux0HEnH_E) ![](https://drive.google.com/uc?export=view&id=1yM1zoBJK2ahXr7Urq1l7wabNkRcywoYz)

### Step 2
1. Running YOLOv7_Custom_Detect.ipynb to classify and evaluate different yoga pose
* The trained weight (best.pt) and modified .py file for detection (detect.py) are stored in the yolov7_custom folder
* MoveNet lightning model (lite-model_movenet_singlepose_lightning_tflite_float16_4.tflite) was adopted for pose evaluation. Further details [link text](https://tfhub.dev/google/movenet/multipose/lightning/1)

### Sample output
![](https://drive.google.com/uc?export=view&id=1uiDuYgg8dFci2DkT1bZ34wZ8yfbToZSK) ![](https://drive.google.com/uc?export=view&id=1U5oD6SBuyCByD_CHonlgK09oB6fH0EgP)

#### For further details, please browse the YOLOv7_Custom_Detect.ipynb file
