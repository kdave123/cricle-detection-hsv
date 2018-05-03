# cricle-detection-hsv
Implementing Circle detection in Python ( OPENCV )

Convert input Image to HSV form
Covert to grayscale
Apply preprocessing steps
Find circles using cv2.HoughCircles

findCircularObjects function plots circles with max diameters ie. in a descending order.
It does not plots the circle if center lies inside other (previously) plotted Circle. Thus avoiding detection(plotting) of multiple circles for a same object.
