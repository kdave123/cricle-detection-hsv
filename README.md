# cricle-detection-hsv
Implementing Circle detection in Python ( OPENCV )

Convert input Image to HSV form
Covert to grayscale
Apply preprocessing steps
including :
1. Gaussain Blur to smooth image(reduce Noise)
2. Canny Edge for detecting edges.

Basic Morphological operations might be used :
1. Erode- Erodes Edges (reduce noise , seperate elements)
2. Dilate- Widens the edges (as per kernel)

Find circles using cv2.HoughCircles

findCircularObjects(circles) function plots circles with max diameters first ie. in a descending order.
It does not plots the circle if center lies inside other (previously) plotted Circle. Thus avoiding detection(plotting) of multiple circles for a same object.
