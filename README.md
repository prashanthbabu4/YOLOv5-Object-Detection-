# YOLOv5 Object Detection

## 1. Clone YOLOv5 from GitHub

```python
!git clone https://github.com/ultralytics/yolov5.git
```

First, I downloaded the YOLOv5 project from GitHub using the git clone command. It creates a folder named yolov5 in the current directory. This folder contains the files needed to run the object detection model.

## 2. Install Required Packages

```python
!pip install -r requirements.txt
```

After downloading the project, I installed the required packages using the requirements.txt file. These packages help to run the YOLOv5 model. It includes libraries like PyTorch, OpenCV, NumPy and other dependencies.

## 3. Change the Directory

```python
%cd /content/yolov5
```

Here, I changed the working directory to the yolov5 folder. This helps me to access and run the Python files available inside the project.

## 4. Perform Object Detection

```python
!python detect.py --weights yolov5s.pt --source "/content/istockphoto-930694108-612x612.jpg"
```

In this step, I used the YOLOv5 pre-trained model to detect objects in an image.

- `detect.py` is used to perform object detection.
- `yolov5s.pt` is the pre-trained YOLOv5 small model.
- `--source` specifies the image location.

After running the command, the model detects the objects in the image and shows bounding boxes, object names and confidence scores.

## 5. Result

The YOLOv5 model successfully detects objects from the given image. The detected output image is saved in the runs/detect folder.

## Conclusion

I learned how to download YOLOv5 from GitHub, install the required packages and run object detection using a pre-trained model. 

Before Pridiction.

<img width="612" height="459" alt="istockphoto-930694108-612x612" src="https://github.com/user-attachments/assets/f7780264-6e5e-40c7-ac37-ac06ae275f50" />
