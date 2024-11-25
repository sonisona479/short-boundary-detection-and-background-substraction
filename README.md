# short-boundary-detection-and-background-substraction
Boundary detection, also known as edge detection, is a process in computer vision and image processing that identifies significant transitions in intensity or color within an image. These transitions often correspond to the boundaries of objects within the image. Common edge detection algorithms include:

Sobel Operator:

Uses convolutional kernels to detect horizontal and vertical edges.

Canny Edge Detector:

A multi-step algorithm that involves noise reduction, gradient calculation, non-maximum suppression, and edge tracking by hysteresis.

Background Subtraction
Background subtraction is a technique used in computer vision to separate foreground objects from the background in a sequence of images or video. It is commonly used in applications like video surveillance, gesture recognition, and object tracking. The main steps typically include:

Background Modeling:

Create a model of the background by averaging multiple frames or using statistical methods like Gaussian Mixture Models (GMM).

Foreground Detection:

Subtract the background model from the current frame to detect changes (foreground objects).

Post-Processing:

Apply techniques like morphological operations to refine the detected foreground, removing noise and filling gaps.

Summary
Boundary Detection: Focuses on identifying the edges or boundaries of objects within a single image.

Background Subtraction: Separates moving objects (foreground) from the static background in video sequences or image streams
