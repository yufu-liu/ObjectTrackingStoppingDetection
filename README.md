# Object Tracking and Stopping Detection with 36 surveillance cameras 
## Features
1. Analyzed the distribution of objects across scenes, temporal and spatial information.
2. Augmented images to improve lighting and occlusions by blurring, hue and saturation adjustment, CutMix, and Mix Up.
3. Utilized YOLO_v8n with IoU calculation for object tracking and counting, and integrated Farneback optical flow for stopping detection.
4. Used Eigen-Cam to generate saliency maps for feature and failure explanation.

## Details for analysis, results and discussion, and future work
https://drive.google.com/file/d/1Mn5FbOCOap3cxIrPNtx_Gj6kFmhy4WXI/view?usp=sharing 

## Reference
1. Dana36 dataset:
https://vision.fe.uni-lj.si/RESEARCH/dana36/index.html

2. Eigen-Cam for YOLO_v8:
   https://github.com/rigvedrs/YOLO-V8-CAM 
