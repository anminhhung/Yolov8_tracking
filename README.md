# yolov8 & tracking

### Setup
```
pip install -r requirements.txt
```

Download yolov8 model [link](https://github.com/ultralytics/ultralytics)

### Run code
```
python3 yolo/v8/detect/detect_and_track.py model=yolov8n.pt source=video.mp4 show=True save=True
```

Output Video Save at "runs" dir