# Traffic Sign Detection and Classification Using ResNet

## Project Overview
This project implements a traffic sign detection system using a modified ResNet architecture. It is designed to accurately classify traffic signs into various categories like traffic lights, stop signs, crosswalk signs, and speed limit signs, and to detect their locations within an image frame.

### Features
- Utilizes the first 8 layers of ResNet as the backbone for feature extraction.
- Includes a classifier head for traffic sign classification.
- Employs a prediction head for determining the 2D bounding box coordinates of traffic signs.
- Tested on both pretrained (ImageNet) and not pretrained ResNet models.
- Evaluation metrics include Average Precision and Average Intersected Fraction (AIF).

## Installation
Make sure you have pytorch installed.
To set up the project environment:

```bash
git clone https://github.com/jwala1998/Traffic-sign-detection-and-classification.git
cd traffic-sign-detection-resnet

