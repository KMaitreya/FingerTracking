# FingerTracking

This is a finger tracking python program. It uses computer vision to track the movements of your palm using 21 reference points, out of them 5 are used for the tip of the fingers. It is made with the help of mediapipe(https://google.github.io/mediapipe/solutions/hands) a library built by google.

Reference points for the fingertips-

1)Thumb->4

2)Index->8

3)Middle->12

4)Ring->16

5)Pinky->20

Download mediapipe with the following command- pip install mediapipe

The palm is tracked using 21 reference points. These reference points are predefined. The reference points are as follows-

![image](https://user-images.githubusercontent.com/47482433/122686109-28838000-d22d-11eb-83c0-a2d5a465c096.png)

After executing the program a camera window will open up, you will be able to see your the chosen fingertip being tracked in this camera window, a pink circle will indicate the chosen fingertip. The program is able to track the same fingertip on 2 palms at a time. This program also shows the frame rate in the top left corner of the camera window once the program is executed.

Libraries used-> opencv(cv2), mediapipe, time.
