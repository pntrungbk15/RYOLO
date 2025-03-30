# Oreinted Object Detection
This repository is a collection of deep learning applications for oreinted object detection.

```bash
python main.py --yaml_config configs/ryolov1/dota.yaml
```

## Info
+ The repository includes RYOLO versions from RYOLOv1 to RYOLOv11 and RYOLOX.
+ The dataset supports data processing in the following formats: VOC, COCO, YOLO.
+ Dataset augmentation options include YOLO-style augmentation (yolo_aug) and SSD-style augmentation (ssd_aug).
+ Model performance evaluation is available using mAP metrics and confusion matrix analysis.
+ Various models trained with multi-scale settings

## Research Models
![](assets/models.jpg)

## Structure
![](assets/code_structure.jpg)

## Demo
Dataset Augmentation:
+ SSD Augmentation
![](assets/ssd_aug.gif)

+ Yolo Augmentation
![](assets/yolo_aug.gif)

Model Performance Evaluation
+ mAP metric:
<p align='center'>
    <img width='1500' src='assets/mAP.jpg'>
</p>

+ Confusion matrix:
<p align='center'>
    <img width='1500' src='assets/confusion_matrix.png'>
</p>

## Demo

### Test .pth & .onnx Model
```bash
voila "test_model.ipynb" --port 8866 --Voila.ip 127.0.0.1 --show_tracebacks=True
```

## Installation

To use these applications, you need to have Python and several Python packages installed. To install the required packages, use the following command:
```bash
pip install -r requirements.txt"
```