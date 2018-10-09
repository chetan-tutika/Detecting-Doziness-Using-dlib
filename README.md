# Detecting-Doziness-Using-dlib
Here we use dlib library to detect if someone is about fall asleep or not and to indicate them about their state. This can be used in real-time while driving or while operating machinery which would require the user to be alert
## Results
![screenshot-36](https://user-images.githubusercontent.com/41950483/46689335-a2829080-cbcd-11e8-89b7-f96d539f728c.png)<br />
![screenshot-40](https://user-images.githubusercontent.com/41950483/46689336-a44c5400-cbcd-11e8-8376-561dddd9f195.png)<br />

The key factor in this project is the eye aspect ratio. The eye aspect ratio is the ratio of distances between the vertical eye landmarks and the distances between the horizontal eye landmarks. This concept was shown in Soukupová and Čech’s 2016 paper, Real-Time Eye Blink Detection using Facial Landmarks<br />
Convex hulls around the eyes are displayed for easy visualizations.
