This Python script creates a simple security camera system using OpenCV and a webcam to detect motion. When significant movement is detected, it triggers an audible beep alert. The program continuously monitors two consecutive frames from the camera, calculates their difference to detect changes, and highlights areas where motion occurs.

How it Works:

Motion Detection: The script calculates the difference between consecutive frames to detect any movement in the camera's view.
Alert Trigger: If the detected movement is large enough, an audible beep sound plays to signal that motion was detected.
Live Video Feed: A processed video stream displays the motion-detected areas in a binary (black and white) format.
Exit Option: The program runs until the 'ESC' key is pressed to exit.
Requirements: This script requires Python, OpenCV for video processing, and winsound (available only on Windows) for the alert sound.
