#  <p align =center>Human Activity Recognition using RGB-D videos</p>
<p align="center">
  
</p>
## About
Human activity recognition uses external video sensors to classify distinct human activities. Since it allows automatic monitoring and analysis of patient or resident activities in smart environments like smart hospitals and smart homes, researchers have drawn considerable interest in health care, social care, and life care services.
Using an RGB sensor, computer vision has significantly improved in assessing human position and activity. However, depth sensors have become more important in human pose estimation over the following ten years. Additionally, numerous RGB-based efforts have been achieved after the initial techniques focused on estimating skeletal joints. Despite all the progress in RGB-based pose estimation, the availability of depth can still be of great use for the pose estimation task.  

## Features of RGB-D videos over RGB videos

There are four major challenges to vision based human action recognition. These are occlusions, cluttered backgrounds, shadows, and varying illumination conditions that can produce difficulties for motion segmentation and alter the way actions are perceived. 

1. SHADOWS : Even for RGB images featuring a human shadow, the mediapipe may create a 3D skeleton. The system's accuracy suffers as a result. Since the depth camera does not capture object shadows, it may be used to remedy this issue.
2. <p align="center">
<img  width="400" src="https://github.com/sankalp20436/Human-Activity-Recognition/blob/main/images/shadow.jpg" alt="Material Bread logo">
  </p>
2. ILLUMINATION : Mediapipe is not able to extract the skeleton from the video if there is high intensity illumination present in the background and as depth camera uses IR sensors to create video not much distortion is seen.
<img  width="400" src="https://github.com/sankalp20436/Human-Activity-Recognition/blob/main/images/illumination.jpg" alt="Material Bread logo">
3. CLUTTERED BACKGROUND : In RGB videos, mediapipe cannot separate a person's backdrop from their features if the two are similar, making it impossible to extract features. However, since depth movies already have depth information, this similarity is eliminated.
<img  width="400" src="https://github.com/sankalp20436/Human-Activity-Recognition/blob/main/images/clutteredbg.jpg" alt="Material Bread logo">
4.OCCLUSION : Occlusion, or when one item is blocked by another, prevents mediapipe from creating correct skeletons since it is unable to distinguish between the various entities. However, in-depth video can distinguish between two objects with ease because they will both have different depths.
<img  align="center" width="400" src="https://github.com/sankalp20436/Human-Activity-Recognition/blob/main/images/occlusion.jpg" alt="Material Bread logo">
 

