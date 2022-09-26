# CS231.M13.KHCL
This is an object detection project that uses YOLOv5-m and Faster R-CNN to classify 11 classes:
1) biker
2) car
3) pedestrian
4) trafficLight
5) trafficLight-Green
6) trafficLight-GreenLeft
7) trafficLight-Red
8) trafficLight-RedLeft
9) trafficLight-Yellow
10) trafficLight-YellowLeft
11) truck

Models' weights:
Weights for YOLOv5-m pretrained models:
- After 100 epochs: https://drive.google.com/drive/folders/1qg_dC4M8DtgV_bXB45hEFss_pf-nBSAO?usp=sharing
- After 125 epochs: https://drive.google.com/drive/folders/1BQhF9y49Lw8jyYCc7jLHYp1owSMDHCov?usp=sharing
- After 200 epochs: https://drive.google.com/drive/folders/1_Vm3_lMeghW2IAD-5dHdwD7BtQYSXf8P?usp=sharing
Weights for YOLOv5-m trained from scratch:
- First 100 freezed epochs: https://drive.google.com/drive/folders/11hxToq1gzfnuuSz2Vtp0-1iQTxjOVaPx?usp=sharing
- Second 100 unfreezed epochs: https://drive.google.com/drive/folders/1TXkYCJ101J6eeiNEB1c7DO4KAr3kTpGc?usp=sharing

Source code:
- YOLOv5-m: https://github.com/ultralytics/yolov5
- Faster R-CNN: https://github.com/ppriyank/Pytorch-CustomDataset-FasterRCNN
