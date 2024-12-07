# Haris-corner-Detection-Algorithm

# Harris Corner Detection Code 1

This project implements Harris Corner Detection on multiple images. The detection algorithm is used to identify corners or interest points in images. These points are often useful in various computer vision tasks such as image matching, object recognition, and motion tracking.

# Features

**Harris Corner Detection:** Detects corners in an image based on the Harris corner detection algorithm.

**Multiple Image Processing:** Processes multiple images and detects corners in each image.

**Visualization:** Displays images with detected corners marked in red.

# How It Works

**Harris Corner Detection:** The algorithm detects corners by calculating the eigenvalues of the second moment matrix of the image. It uses a sensitivity factor (k) and a threshold to classify corners.

**Thresholding:** The corners are highlighted in red on the original image if the corner strength exceeds a defined threshold.

**Processing Multiple Images:** The program processes multiple images, detects corners in each, and displays the result.

# Requirements

o Python 3.x

o OpenCV (cv2): For image processing and corner detection.

o NumPy: For matrix operations.

o Matplotlib: For visualizing results.
