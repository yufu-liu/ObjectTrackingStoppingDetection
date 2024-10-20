# Object Tracking and Stopping Detection with 36 surveillance cameras 
## Features
1. Data Analysis
   - The distribution of objects across scenes
   - The distribution of lighting condition across different scenes
   - The distribution of objects across different camera properties
   - The temporal analysis and spatial analysis of different objects.
2. Pre-processing
   - Augmented images to improve lighting and occlusions by blurring, hue and saturation adjustment, CutMix, and Mix Up.
3. Fine-tuning, tesing, and inference
   - Utilized YOLO_v8n with IoU calculation for object tracking and counting, and integrated Farneback optical flow for stopping detection.
4. XAI
   - Used Eigen-Cam to generate saliency maps for feature and failure explanation.

## Details for analysis, results and discussion, and future work
https://drive.google.com/file/d/1Mn5FbOCOap3cxIrPNtx_Gj6kFmhy4WXI/view?usp=sharing 

## Examples
1. https://drive.google.com/file/d/1FL7-YNwq1g3516-OJUZQ9FYRD-fvo4HU/view?usp=sharing
2. https://drive.google.com/file/d/1QfY2Cl_pDv-E7b7u90KvlQ_h6jjHtrj3/view?usp=sharing
3. https://drive.google.com/file/d/1WLN9-zxE4f4S4tGorXCsls5m1Qcz6RYD/view?usp=sharing

## Reference
1. Dana36 dataset:
https://vision.fe.uni-lj.si/RESEARCH/dana36/index.html

2. Eigen-Cam for YOLO_v8:
   https://github.com/rigvedrs/YOLO-V8-CAM 
