Color-Based Automated Sorting System
<br>

A vision-based object classifier that sorts using color detection and a single actuator.<br>
--> Introduction<br><br>

-This project is a real-time object classifier that uses a conveyor belt and computer vision to sort objects based on color (Green, Blue, or Trash). Built using OpenCV, Arduino Uno, and a custom servo-controlled arm.<br><br>

-The object is moved by a conveyor, captured via webcam, classified using HSV filtering, and sorted into bins via a 3D-printed servo-controlled arm.<br>
--> Instructions<br><br>

1) Place an object on the conveyor belt.<br>
2) The color of the object is detected using OpenCV python.<br>
3) Arduino receives signals ('G', 'B', 'T') via serial and actuates the sorting arm.<br>
4) Object is sorted into the appropriate bin (Green, Blue, or Trash).<br>
--> Hardware Required:<br><br>

-Arduino Uno<br>
-Servo Motor (for sorting arm)<br>
-Gear Motor (for conveyor belt)<br>
-Webcam<br>
-Ultrasonic Sensor (for object detection trigger)<br>
-3D-printed Sorting Arm<br>
-Conveyor Belt Setup
