# Human-Pose-Estimator


Pose estimation for knee bend exercise


Here is a  robust algorithm to calculate successful rep count for knee bend exercise using mediapipe pose model and opencv.

How model is working :

_Angle value is printed on the knee .

_when angle of the leg is more than 140  degree message “make your knee bent “   is printed and timer value  is zero .

_when patient starts to bend his knee less than 140 degree message “your are in a right position” is printed and timer starts to run till it reaches 8 sec then message “successful rep,stretch your leg “ is printed. timer will not reset till patient stretch his leg first then he can bend it again to make another rep .

_if patient stretch his/her leg before timer reaches 8 sec timer will reset

