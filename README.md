This Repository is based on the FaceDetection:
https://github.com/emara-geek/real-time-face-detection-using-opencv-with-java/issues/1#issuecomment-289291259
After cloning this Repository you require to download the Java Library openCV:

https://opencv.org/

Import the the jar File in ..\opencv\build\java as Library under Project Properties
Maven seems not to be supported correctly yet.

Add VM Option under Project Properties -> Run:
-Djava.library.path="PathToFolder\opencv\build\java\x64"

