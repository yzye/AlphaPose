# AlphaPose

This projects implement Alpha Pose. It shows good performance on our test datasets. Alpha Pose is a very Accurate Real-Time multi-person pose estimation system.

<p align="center">
  <img src="/AlphaPose_standing1.gif" alt="Pedestrian Detector in action"></img>
</p>

### 1. Installation 
Refer to the instructions from this [link](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html). 

### 2. Data Preparation

We upload the test vedio `standing1.MP4` in `example/test/vedio` folder. And the output of the procesed vedio will locate at the `example/res` directory.

### 3. Model Selection

RMPE: Regional Multi-Person Pose Estimation

### 4. Perform the object detection
Run the following command.
```
python3 video_demo.py --video examples/vedio/standing1.MP4 --outdir examples/res --save_video --sp
```
