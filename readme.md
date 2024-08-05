# Pencil Sketch with Python

This project demonstrates how to convert an image into a pencil sketch using Python and OpenCV.

## Requirements

- Python 3.x
- OpenCV


------------------------------------------------------------------------------------------------------
 
 
## Code Explanation

The script performs the following steps:

~Read the Image: Loads the image using cv2.imread().
~Display the Original Image: Uses cv2.imshow() to display the original image.
~Convert to Grayscale: Converts the image to grayscale using cv2.cvtColor().
~Invert the Grayscale Image: Inverts the grayscale image.
~Apply Gaussian Blur: Smoothens the inverted image using cv2.GaussianBlur().
~Create Pencil Sketch: Blends the grayscale image with the inverted blurred image to produce the pencil sketch effect.
~Display Results: Shows the original image and the pencil sketch side by side.


-------------------------------------------------------------------------------------------------------


## Sample Output

The script will display the following images:

~The original image
~The grayscale image
~The inverted image
~The blurred image
~The final pencil sketch
