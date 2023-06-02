# MOTION-DETECTION-USING-OPENCV
The program is an implementation of motion detection using OpenCV in Python. It uses a video source (such as a webcam or video file) to detect and highlight moving objects in the scene. The main steps of the program are as follows:

1. It captures frames from the video source and converts them to grayscale.
2. It compares each frame with a reference frame to determine the differences (motion) between them.
3. A threshold is applied to the difference frame to filter out small variations and enhance the motion regions.
4. Contours are detected in the thresholded frame to identify connected components (objects) representing motion.
5. Contours with areas below a certain threshold are ignored as noise, while larger contours are outlined with bounding rectangles.
6. The resulting frame with motion rectangles is displayed in a window.
7. The program continues this process until the 'q' key is pressed to exit.
8. After exiting the loop, the video capture object is released, and the windows are closed.

Overall, the program provides a simple motion detection mechanism that can be used for various applications, such as surveillance systems or activity monitoring.

RESULTS:

![image](https://github.com/Ra-Chit/MOTION-DETECTION-USING-OPENCV/assets/83090070/7baf6aba-919f-40ad-a2ff-309e4a699ae3)



