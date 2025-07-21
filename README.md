YOLOv7 Threat-Detection
A threat detection system using the YOLOv7 object detection framework — trained to recognize 9 types of weapons in images.

![YOLOv7][(https://github.com/WongKinYiu/yolov7)]

Project Overview
This repository contains code and configuration for training and running a YOLOv7 model to detect weapons including rifles, handguns, grenades, knives, and more.

Model Details
Model Architecture: YOLOv7
Input Size: 416×416
Number of Classes: 9
Classes:
Automatic Rifle
Bazooka
Handgun
Knife
Grenade Launcher
Shotgun
SMG
Sniper
Sword


1. Install dependencies:
   pip install -r requirements.txt

2. Run inference using bash:
   python detect.py --weights best.pt --conf 0.25 --img-size 640 --source path/to/image.jpg --data data.yaml
=======

