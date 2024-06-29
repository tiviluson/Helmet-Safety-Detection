# YOLOv10 Helmet Safety Detection Model

## Overview
This repository contains the original, pretrained YOLOv10 model. Later on, the model is fine-tuned against a custom dataset for detecting safety equipment and personnel in work environments. The model is specifically trained to identify three classes: head, helmet, and person, which are crucial for ensuring workplace safety compliance.

## Model
The YOLOv10 (You Only Look Once, version 10) is an advanced deep learning model known for its speed and accuracy in object detection tasks. This model has been fine-tuned on a custom dataset to recognize heads, helmets, and persons with high precision.

## Get started
1. Execute each cell in *YOLOv10_Helmet_Safety_Finetuning.ipynb*
1. In **Step 7**, a variable named `TRAIN` defaults to `False`.
    - If you want to fine-tune the model, set this variable to `True`.
    - If you want to use the fine-tuned weights, leave it as `False`. The fine-tuned weights, as well as intermediate and final results, eveluations, charts, etc. are available in `finetuned\detect\train`.
1. Continue executing cells to Step 9.