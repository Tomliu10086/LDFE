# YOLO-LDFE
Implementation of paper - YOLO-LDFE：Lightweight Object Detection Model Based on Improved Dense Connection Modules


![image](coal_mine_figure/Rep-1.png)
![image](coal_mine_figure/Rep-2.png)
![image](coal_mine_figure/Rep-3.png)

# Requirements
```
$ pip install -r requirements.txt
```

# Training
Run commands below to reproduce results on URPC2021 dataset
```
$ python train.py --data data\Rep-YOLO_MPdataset.yaml --cfg cfg\training\Rep-
YOLO.yaml --weights '' --batch-size 8```

# Testing
```
$ python test.py
```

# Inference
`detect.py` runs inference on coal mine source
```
$ python detect.py
```
