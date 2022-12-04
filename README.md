
## Usage
- add your YoloV5 .pt trained file
- use your webcam

### If you want to use your own local YoloV5 Folder 
- Change line 27 to this
```python
model = torch.hub.load('ultralytics/yolov5', 'custom', source="local", path=model_name, force_reload=True)
```

### For run
- $ python3 main.py
