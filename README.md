# PCB-Defect-Detection (POC)
Problem Statement: Automatic Visual Inspection with custom object detection to replace any possible manual visual inspection in PCB manufacturing for common PCB Defects.

# Dataset
I used a very less number of images and relabeled (annotation) also from this huge dataset which is available at https://www.dropbox.com/s/32kolsaa45z2mpj/PCB_DATASET.zip?dl=0.
Contributer of that dataset: https://github.com/Ixiaohuihuihui/Tiny-Defect-Detection-for-PCB

# Object Detection
I made some changes in this code. https://github.com/nicknochnack/TFODCourse. 

# Model
Pretrained model ssd_resnet50_v1_fpn_640x640_coco17_tpu-8 used to train on defects. Trained on colab GPU with very less number of images. After training more images, it can be a smaller box around the defective thick track.

![image](https://user-images.githubusercontent.com/75474944/123749489-1d86ba80-d8d3-11eb-9117-06269ab98ee5.png)
