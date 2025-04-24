Color-Based Automated Sorting System

A vision-based object classifier that sorts using color detection and a single actuator.
--> Introduction

-This project is a real-time object classifier that uses a conveyor belt and computer vision to sort objects based on color (Green, Blue, or Trash). Built using OpenCV, Arduino Uno, and a custom servo-controlled arm.

-The object is moved by a conveyor, captured via webcam, classified using HSV filtering, and sorted into bins via a 3D-printed servo-controlled arm.
--> Instructions

1) Place an object on the conveyor belt.
2) The color of the object is detected using OpenCV python
3) Arduino receives signals ('G', 'B', 'T') via serial and actuates the sorting arm.
4) Object is sorted into the appropriate bin (Green, Blue, or Trash).
--> Hardware Required:

-Arduino Uno
-Servo Motor (for sorting arm)
-Gear Motor (for conveyor belt)
-Webcam
-Ultrasonic Sensor (for object detection trigger)
-3D-printed Sorting Arm
-Conveyor Belt Setup
