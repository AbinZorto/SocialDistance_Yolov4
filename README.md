# Social Distancing using YOLOv4
Implementation of YOLOv4 algortihm with darknet for the purpose of enforcing social distancing guidelines

For instructions on how to install darknet YOLOv4
https://blog.roboflow.ai/training-yolov4-on-a-custom-dataset/

After Installation
Place Distance.py file and Input Folder in darknet folder

```console
cd darknet
```

Then run code as so
```console
python Distance.py ./Input/test.mp4
```

To test on custom video add video to input folder replace './Input/test.mp4' with your video path and run

![alt text](https://github.com/AbinZorto/SocialDistance_Yolov4/blob/master/output.gif)

Supports automatic calibration of distance which allows for use on novel video data 
