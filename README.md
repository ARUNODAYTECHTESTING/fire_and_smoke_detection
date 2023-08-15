# Deep Learning-Based Fire Vehicle Detection and Real-Time Warning System
You can run code with your own PC/Notebook/... or on Google Colab.
<a href="https://colab.research.google.com/github/ytl0623/monai_wholeBody_ct_segmentation/blob/master/monai_wholeBody_ct_segmentation.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>

## Create a virtual environment
```
conda create -n [NAME] python==3.9
```

## Start the environment
```
conda activate [NAME]
```

## Clone Repository
```
git clone https://github.com/ytl0623/yolov8-fire-car-and-smoke-detection.git
```

## Go to the cloned folder
```
cd yolov8-fire-car-and-smoke-detection
```

## Install the dependencies
```
pip install -r requirements.txt
```

## Go to the working directory
```
cd ultralytics/yolo/v8/detect/
```

## Modify E-mail address
Change your desire email address in ```send_email.py```.
```
your_email =
your_password =
send_email_to =
```

## Execute inference
Change the input of the image/video/rtsp/..., what ever you want.
```
python main.py
```

## Results
The output image is like the below.

If the model detected the fire and smoke, the command line shows output ```Warning Fire!!! Send Email!``` and it will send email to desire person with the image contains bounding box.

## Reference
- https://github.com/ultralytics/ultralytics
- https://github.com/gaiasd/DFireDataset
- https://github.com/open-mmlab/mmyolo