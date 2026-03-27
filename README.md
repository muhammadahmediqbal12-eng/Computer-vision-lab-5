# Computer-vision-lab-5
Edge Detection Techniques
This notebook demonstrates various edge detection techniques using OpenCV and Python. Edge detection is a fundamental image processing technique used to identify points in a digital image where the image brightness changes sharply or has discontinuities. These discontinuities are typically organized into a set of curved line segments referred to as edges.

Techniques Covered:
1. Sobel Edge Detection
Description: The Sobel operator is a discrete differentiation operator that computes an approximation of the gradient of the image intensity function. It highlights regions of high spatial frequency, which often correspond to edges.
Application: Used for general edge detection, particularly in images like road or lane photos to identify prominent lines.
2. Prewitt Edge Detection
Description: The Prewitt operator is similar to the Sobel operator but uses a simpler approximation for the image gradient. It is a 3x3 filter used to detect edges in horizontal and vertical directions.
Application: Demonstrated with aerial or satellite images to identify significant changes in intensity that correspond to geographical features or structures.
3. Canny Edge Detection
Description: The Canny edge detector is a multi-stage algorithm known for its ability to detect a wide range of edges in images while suppressing noise and providing good localization. It involves Gaussian smoothing, gradient computation, non-maximum suppression, and hysteresis thresholding.
Applications:
General Images: Applied to traffic signs or street scenes to extract object boundaries.
Medical Images: Used on grayscale medical images (CT/MRI scans) to highlight anatomical structures or anomalies.
Road/Lane Images: Implemented with an initial Gaussian blur to enhance lane line detection in road images, proving robust against noise.
How to Use:
Each section of the notebook allows you to upload an image and then applies the specified edge detection algorithm, displaying both the original grayscale image and the resulting edge-detected image.
