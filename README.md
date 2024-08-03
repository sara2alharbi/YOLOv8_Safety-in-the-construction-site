# YOLOv8 Object Detection (safety in the construction site)

## Project Overview:
Ensuring safety and security in facilities is paramount. I recently embarked on a project using the latest YOLOv8 model and Roboflow to create a cutting-edge object detection system for enhancing facility safety and security.

## Dataset Preparation: 
Collected and annotated images of potential security threats and safety hazards using Roboflow. Applied data augmentation to enhance the dataset.

* The YOLOv8 model achieved impressive performance metrics:

  Overall Performance: Precision: 0.78, Recall: 0.772, mAP50: 0.829.

* Specific Classes:
  
  Helmet: Precision: 0.892, Recall: 0.905, mAP50: 0.936.
  
  No Helmet: Precision: 0.805, Recall: 0.636, mAP50: 0.803.

  No Vest: Precision: 0.713, Recall: 0.802, mAP50: 0.83.

  Person: Precision: 0.86, Recall: 0.896, mAP50: 0.917.

  Vest: Precision: 0.838, Recall: 0.865, mAP50: 0.893.

These results show the system's capability to accurately detect safety gear and identify compliance issues, which is crucial for maintaining high safety standards in facilities.

## Model Training: 
Trained the YOLOv8 model with the prepared dataset. 
