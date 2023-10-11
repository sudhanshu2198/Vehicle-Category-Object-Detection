

# Vehicle Category Object Detection using SSD 

The goal of automated surveillance and monitoring systems is to remove the need of human labor for simple
vision based tasks that can be performed by a computer or an automated system. One such application is Traffic video analysi system based on computer vision designed to automatically gather important statistics for policy makers and regulators in an automated fashion. These statistics include vehicle counting, vehicle type classification and lane usage monitoring. The core of such system is the detection and classification of vehicles in traffic videos.

![](https://i.ibb.co/4sVh0Rj/download.jpg)

Challenges in correctly detecting and classifying objects. 
- Image are captured at both day and night due to which there will varying  light intensities and  distribution.
- Imbalance in class distribution of different categories of vehicle.

![](https://i.ibb.co/gW4N6YF/1.png)

**The main goal of this project is to develop object detection system utilizing Single Shot Detector (SSD) with vgg18 backbone.**

## 🔗 Links

- [Dataset](https://www.kaggle.com/datasets/sakshamjn/vehicle-detection-8-classes-object-detection/code)
- [Learned Model Weights](https://www.kaggle.com/datasets/sudhanshu2198/vehicle-categorization-detection-earned-weights)
- [Kaggle Notebook](https://www.kaggle.com/code/sudhanshu2198/vehicle-category-object-detection-pytorch)
## 🛠 Skills
Numpy, Matplotlib, Pandas, OpenCV, Pytorch, torchvision, albumentations

## Comparison between Ground truth and Predicted Bounding Boxes
![](https://i.ibb.co/syqZJw0/4.png)

## Results

**The model is trained for 60 epochs using GPU Tesla P-100. It achieved a mean average precision of .57 at IOU=0.5. Non Max suppression is performed on model output using conf_threshold=0.3 and iou_threshold=0.8**

- Mean Average Precision[0.5:0.95:0.05] : 0.5179
- Mean Average Precision @ 0.5          : 0.5697
- Mean Average Precision @ 0.75         : 0.5670

![](https://i.ibb.co/WP8Rz6J/3.png)
![](https://i.ibb.co/JHWjFNx/5.png)




