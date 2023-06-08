# Human-Pose-Estimator


This is an effective method to calculate the number of successful repetitions for the knee bend exercise, using the Mediapipe pose model and OpenCV.

The model operates in the following manner:

-The angle value is displayed on the knee.
-If the leg angle exceeds 140 degrees, a message "make your knee bent" is displayed, and the timer is set to zero.
-When the patient begins to bend their knee to less than 140 degrees, a message "you are in the right position" is displayed, and the timer starts running until it -reaches 8 seconds. Then, a message "successful rep, stretch your leg" is displayed. The timer will not reset until the patient stretches their leg first, and then they can bend it again to complete another repetition.
-If the patient stretches their leg before the timer reaches 8 seconds, the timer will reset.


Video decribes how it works : https://drive.google.com/file/d/1yvLLWOeSIJxYFFw1NxBoOm7zDjU6GHQS/view?fbclid=IwAR1yXnUVFiRePy8sIEyNoyxOknwDOMbSmPVw56PdqiIkrI3Rvr8D-fsjevY

