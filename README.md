## "Air canvas" - A computer vision project implemented using OpenCV
This interactive canvas is created using OpenCV and Python, allowing you to draw effortlessly by waving a colored marker in front of a camera. OpenCV, a powerful computer vision library, is utilized to detect and track the movement of the marker in real-time.
Before you get started, make sure you have Python, OpenCV, and Numpy installed on your system.
### :one: Introduction
  Learn about the project's foundation in computer vision and OpenCV.Understand the use of color detection and tracking techniques for marker movement.
### :two: Prerequisites
Python, OpenCV and Numpy

### :three: Steps to be followed
1.Read frames and convert them to the HSV color space for easy color detection.
2.Set up the canvas frame, attach ink buttons, and use track bar values to determine the marker mask.
3.Apply morphological operations for mask preprocessing, including erosion and dilation.
4.Find contours and center coordinates for the largest contour, storing them for drawing on the canvas.
5.Draw the array of points on the canvas and frames.
Output:
### :four: Output
Experience the real-time drawing on the Air Canvas as you move the colored marker.

### :five: Conclusion
This project showcases the creation of an Air Canvas using OpenCV and Python, incorporating color detection, segmentation, thresholding, logical operations, and various image processing techniques.
