# This project is prepared for Pose Classification using deep learning methods to obtain meaningful interpretations of a pose by controlling the relative positions of various body parts. 

Please consider the following explanations while working on the code.

1. First, we should have a video with two main poses. After this video is divided into photos using 'ffmpeg', two folders should be prepared as Up and Down containing the appropriate poses.

2. Csv file should be prepared using the created folder and pose detection model (blazepose). These data clearly predict two additional virtual key points that precisely define the center of the human body, the rotation and the scale as a circle.

![landmarks](https://user-images.githubusercontent.com/63105388/222617300-8677bd3f-f827-4a02-a00b-b90a02a0a5c3.png)

To preparing this data, examine the "creating_csv_file.ipynb" file.

3. 
