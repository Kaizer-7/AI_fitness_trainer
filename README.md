# OPTIMAL FITNESS  
This is a AI virtual gym trainer
Just like a personal gym trainer, this aims to help you keep track of the number of exercise repetition you performed, along with a pose correction feedback mechanism to correct your pose if needed.
At the end of your exercise, a chart will be displayed to show you your performance throughout the exercise. 📈

Exercises supported: Squats, Arm Curl, Situp

Make sure that you have enabled the camera on your computer before proceeding. 💻 
Instructions:
1. Click on the 'Kernel' tab above and select 'Restart and Run All'.
2. When prompted input, enter either '1', '2', or '3' then hit the 'Enter' key to choose the exercise that you would like to perform.
3. A new window will open up, make sure to select that window.
4. Proceed to perform your exercise infront of your webcam.

Make sure your whole body is visible in the frame when performing your exercise!

After your exercise session:
1. Press 'q' to stop the program.
2. A chart displaying your performance will appear at the bottom of the notebook.

Screenshot of exercise tracking chart

![optimal_fitness](https://github.com/HeshiyaGaya3/optimal_fitness/assets/114100105/b8c407eb-3844-44ad-9e3b-eec6927fcf3c)

# Install dependencies if haven't already

    !pip install mediapipe opencv-python

The MediaPipe Pose Landmarker task requires the mediapipe PyPI package:

    !python -m pip install mediapipe

Import the following classes to access the Pose Landmarker task functions:

    !import mediapipe as mp
    !from mediapipe.tasks import 
    !from mediapipe.tasks.python import vision


