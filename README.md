# PCB-Defect-Detection
**Problem Statement: Automatic Visual Inspection with Custom Object Detection to replace any possible manual visual inspection in PCB manufacturing for common PCB Defects.**

When I was used to designing circuit boards in a smart home product company, I stumbled upon one industry news about AI auto routed PCBs. This was the first use case I stumbled upon but this one was for designers. I searched the same thing on the manufacturing side I got to know about how computer vision can detect defects in PCBs.

This is the bare PCB before soldered components. Most of the time bare circuit boards can be only a fraction of the total cost of PCB with assembled components. But if this bare circuit board has a defect and that defective board gets assembled with components it is a high loss.
So if the circuit board has a defect then it must be captured before it gets assembled. That’s where computer vision comes into the picture.
![image](https://user-images.githubusercontent.com/75474944/143443565-d9a235d2-c5ff-450e-8c48-e3da2b4d8b55.png)


# Dataset & Preprocessing
* I used a very less number of images and relabeled (annotation) also from this huge dataset which is available at https://www.dropbox.com/s/32kolsaa45z2mpj/PCB_DATASET.zip?dl=0.
Contributor of that dataset: https://github.com/Ixiaohuihuihui/Tiny-Defect-Detection-for-PCB. Thanks to their contribution.
* It is a synthetic dataset created in photoshop because Collecting 1000s or 100s of defective images could be a disaster for the manufacturing facility.
* I am using that dataset for the only demonstration purpose in my data science journey rather than any experiments.

# Model 
* Trained on Google Colab GPU with a 288 of images having 6 clasees. 
![image](https://github.com/user-attachments/assets/9120a20b-a74f-466d-911d-0d19f7cb2f84)
