# PCB-Defect-Detection
Problem Statement: AI Visual Inspection with custom object detection to replace any possible manual visual inspection in PCB manufacturing for common PCB Defects.

# Dataset
I used a very less number of images from this huge dataset which is available at https://www.dropbox.com/s/32kolsaa45z2mpj/PCB_DATASET.zip?dl=0.

# Object Detection Pipeline
This object detection pipeline I got from one youtube course which is available at https://www.youtube.com/watch?v=yqkISICHH-U&list=LL&index=29&t=12011s.

# Model
Pretrained mdoel ssd_resnet50_v1_fpn_640x640_coco17_tpu-8 used to train on defects. Trained on colab GPU.
![image](https://user-images.githubusercontent.com/75474944/123749489-1d86ba80-d8d3-11eb-9117-06269ab98ee5.png)
After training more images, it can be a smaller box around the defective thick track.
