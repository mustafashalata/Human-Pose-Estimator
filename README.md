# Human-Pose-Estimator


Pose Estimation for knee bend exercise


Here is a  robust algorithm to calculate successful rep count for knee bend exercise using mediapipe pose model and opencv.

How model is working :

_Angle value is printed on the knee .

_When angle of the leg is more than 140  degree message “make your knee bent “   is printed and timer value  is zero .

_When patient starts to bend his knee less than 140 degree message “your are in a right position” is printed and timer starts to run till it reaches 8 sec then message “successful rep,stretch your leg “ is printed. timer will not reset till patient stretch his leg first then he can bend it again to make another rep .

_If patient stretch his/her leg before timer reaches 8 sec,timer will reset


Video decribes how it works : https://drive.google.com/file/d/1yvLLWOeSIJxYFFw1NxBoOm7zDjU6GHQS/view?fbclid=IwAR1yXnUVFiRePy8sIEyNoyxOknwDOMbSmPVw56PdqiIkrI3Rvr8D-fsjevY

