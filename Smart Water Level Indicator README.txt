 📄 Smart Water Level Indicator

 📌 Project 1

  **PROJECT LINK: https://wokwi.com/projects/435286395599037441

 📌 Problem Statement:

Manual monitoring of water tank levels is inefficient, often leading to overflows or tanks running dry. A smart, automated system is needed to detect and alert users about water levels in real-time.


 📌 Objective:

To design an automatic system using an *ultrasonic sensor* and *Arduino Uno* that detects water levels inside a tank and alerts the user through a *buzzer or LEDs*.


 📦 Requirements:

* Arduino Uno
* HC-SR04 Ultrasonic Sensor
* Buzzer or LEDs
* Jumper Wires
* Breadboard
* (Optional) 16x2 LCD display


 🔌 Circuit Connections:

| HC-SR04 Pin | Arduino Uno Pin |
| :---------- | :-------------- |
| VCC         | 5V              |
| GND         | GND             |
| TRIG        | Digital Pin 9   |
| ECHO        | Digital Pin 10  |

*Buzzer/LEDs:

* Connect to Digital Pin 7
* GND to GND


 📑 *Working Principle:*

* The *HC-SR04 ultrasonic sensor* sends sound waves towards the water surface.
* It measures the time taken for the waves to bounce back.
* The Arduino calculates the *distance to the water surface* using the speed of sound.
* Depending on the distance, it:

  * Activates a *buzzer* or LEDs for different water levels.
  * Can optionally display the status on an LCD display.
* If water level crosses a threshold (like overflow or too low), the system alerts.


 📊 Expected Outcome:

* Real-time display and/or alerts when:

  * Tank is Full
  * Tank is Half
  * Tank is Low
* Prevents water wastage due to overflow.
* Ensures timely refilling when the tank runs dry.
* Simple and effective system suitable for homes, schools, and offices.


 👩‍💻 Author: Hima Siva Sai
 📅 Date: July 2025

