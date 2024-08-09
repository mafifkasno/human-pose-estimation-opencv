# human-pose-estimation-opencv-with-fall-detection
Perform Human Pose Estimation in OpenCV Using OpenPose MobileNet. I fork from https://github.com/quanhua92/human-pose-estimation-opencv and modified abit for fall detection.

![OpenCV Using OpenPose MobileNet](output.JPG)


# How to use

- Test with webcam

```
python fall_detection_iFuzzy.py
```

- Test with image
```
python openpose.py --input image.jpg
```

- Use `--thr` to increase confidence threshold

```
python openpose.py --input image.jpg --thr 0.5
```
