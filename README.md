# Arduino 3.55-Analog Input
## In this assignment you will learn to use analog sensors as input devices.  

---

### Step One: Build the Circuit

Build your circuit according to this schematic:

![pulldown analog circuit](https://github.com/WHS-Robotics-Classes/3.55-Analog_Input/blob/main/Analog_Circuit.PNG?raw=true)

### Step Two: Write the Code

Before you start, review the Arduino Reference page on [`analogRead()`](https://www.arduino.cc/reference/en/language/functions/analog-io/analogread/).  You should also review [`Serial.println()`](https://www.arduino.cc/reference/en/language/functions/communication/serial/println/) as you will need to know how to print something as a hexidecimal number.

1. Copy any starter code provided for you (Starter.ino file) into the [Codebender IDE](https://edu.codebender.cc/class/1ajtp).
2. Modify the code so your sketch does the following:
    - Print the value received by the input pin to the Serial monitor using `Serial.ptintln()` as a hexidecimal number.  (This will look very strange - see my example video below)
    - Delay 250 ms between each cycle.
    - Keep running forever.

Use the video below as a reference.

### Step Three: Debug and Submit

[![3.55_Video](http://img.youtube.com/vi/nPcxHFvlSNA/0.jpg)](https://www.youtube.com/watch?v=nPcxHFvlSNA "3.55-Analog Input Video")

Make sure your prototype behaves the same way as the one in the video. As in the previous assignment, make a new file here on GitHub. Name it 3.55_Analog_Input.ino and Commit it to the repository.
