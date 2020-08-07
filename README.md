# Sports-Player-Detection

A Python computer vision application which tracks sports players given a reel of footage.
It utilizes multiprocessing and the MobileNet SSD detection network.

[![Video of project:](/sports-player-tracker/sports-player-tracker/race.mp4)]

Requirements (Py modules): dlib, imutils, multiprocessing, cv2.
To run on command line (Windows):

This command will run the object detector on the input footage race.mp4 . Replace with your personal footage as wanted.
py multi_object_tracking_fast.py --prototxt mobilenet_ssd/MobileNetSSD_deploy.prototxt --model mobilenet_ssd/MobileNetSSD_deploy.caffemodel --video race.mp4
