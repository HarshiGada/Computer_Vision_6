# Computer_Vision_6
Use feature descriptor to align images

Objective
We will align two given images using the Scale-Invariant Feature Transform (SIFT) algorithm. The steps will involve identifying key points, matching them between images, calculating the Homography matrix, and using it to warp one image to align with the other.

Steps Overview
Task 1: Use SIFT to determine interest points and descriptors for the given images
Task 2: Match key points of the images
Task 3: Generate Homography matrix using matched key points
Task 4: Use the Homography matrix to warp the image to be aligned

Prerequisites
To run the code, ensure you have the following installed:

Python 3.x
OpenCV (cv2 package)
NumPy
Matplotlib (optional, for visualization)


You can install the necessary dependencies by running:
pip install opencv-python numpy matplotlib
