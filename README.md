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


# Object Recognition by Corner Detection  Code 2

This project implements Harris Corner Detection to identify interest points (corners) in images. The algorithm is applied to an original image and compared with several other rotated or modified images to find matches based on detected corners

# Features

**Harris Corner Detection:** Detects corners in an image using the Harris corner detection algorithm.

**Corner Matching:** Compares detected corners in an original image with other images (e.g., rotated or modified versions) to see if they match.

**Visualization:** Displays the original image and the compared images side by side for easy comparison.

# Steps in the Code:

**Harris Corner Detection:** Detect corners in all images.

**Feature Matching:** Match the original image's features to the other images using a brute-force matcher.

**Similarity Scoring:** Count the number of good matches for each image.

**Determine the Best Match:** The image with the highest number of good matches is the rotated version of the original.


