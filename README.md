# AI FITNESS TRAINER  
Exercises supported: Squats, Arm Curl, Situp
Instructions :
1. Click on the 'Kernel' tab above and select 'Restart and Run All'.
2. When prompted input, enter either '1', '2', or '3' then hit the 'Enter' key to choose the exercise that you would like to perform.
3. A new window will open up, make sure to select that window.
4. Proceed to perform your exercise infront of your webcam.

Make sure your whole body is visible in the frame when performing your exercise!

After your exercise session:
1. Press 'q' to stop the program.
2. A chart displaying your performance will appear at the bottom of the notebook.


# Install dependencies if haven't already

    !pip install mediapipe opencv-python

The MediaPipe Pose Landmarker task requires the mediapipe PyPI package:

    !python -m pip install mediapipe

Import the following classes to access the Pose Landmarker task functions:

    !import mediapipe as mp
    !from mediapipe.tasks import 
    !from mediapipe.tasks.python import vision


