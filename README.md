# Motion_Detector
Python/OpenCV script that detect motion on webcam and allows to record it and plot a graph for proper Visualization.

## Description ##
### The Process ###
The trivial idea is to compute the difference between two frames apply a threshold the separate pixels that have changed from the others and then count all the black pixels. Then the average is calculated with this count and the total number of pixels and depending of the ceil the event is triggered or not.

## Requirements ##

1. X86, X86_64, ARMv7 or ARMv8 version of Ubuntu 16.04 or Debian 8 (will most likely work on other Linux based operating systems as well)
2. Python 3.4 or above
3. Camera or Video file
4. Install OpenCV or pip install opencv-python
5. Install Bokeh library or pip install bokeh
