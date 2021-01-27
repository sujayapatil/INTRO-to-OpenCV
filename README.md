# INTRO-to-OpenCV

# Read,write and save Image Using OpenCV In Python
Syntax: cv2.imread(path, flag)

flag: default value is cv2.IMREAD_COLOR

Parameters:

cv2.IMREAD_COLOR or 1: reads the image with RGB colors

cv2.IMREAD_GRAYSCALE or 0: reads the image with gray colors

cv2.IMREAD_UNCHANGED or -1: It reads the image as is from the source. If the source image is an RGB, it loads the image into an array with Red, Green, and Blue channels. If the source image is ARGB, it loads the image with three color components along with the alpha or transparency channel.
