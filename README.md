# EP2 – ESP32-S3 LED Blinking Project

**Student:** Leslie Mbunda  
**Course:** Embedded Programming (EP2)  
**Board:** ESP32-S3 DevKitC-1  
**IDE:** Visual Studio Code  
**Build System:** PlatformIO  
**Framework:** Arduino

## 1. Introduction

This project demonstrates how to control an LED using an ESP32-S3 microcontroller. The project was developed using Visual Studio Code and PlatformIO.

The main objective was to configure the development environment, write an LED blinking program, upload the code to the development board and verify that the LED works correctly.

## 2. Objectives

- Set up Visual Studio Code and PlatformIO.
- Configure the ESP32-S3 development board.
- Understand the purpose of the `platformio.ini` file.
- Write and upload an LED blinking program.
- Test the LED functionality.
- Use Git and GitHub for version control.

## 3. Hardware and Software

### Hardware
- ESP32-S3 DevKitC-1.
- USB cable.
- LED and resistor (if using an external LED).

### Software
- Visual Studio Code.
- PlatformIO IDE.
- Arduino framework.
- Git and GitHub.

## 4. Project Structure

```text
ep2-starter/
│
├── platformio.ini
├── README.md
├── src/
│   └── main.cpp
├── examples/
│   └── session01_plain_led.cpp
└── screenshots/
    └── my-blink.png
```

## 5. PlatformIO Configuration

The `platformio.ini` file contains the configuration required to build and upload the project.

It specifies the development board, platform, programming framework, upload settings and serial monitor speed.

## 6. Implementation

The LED blinking program is written in `src/main.cpp`.

The `setup()` function initializes the LED pin and serial communication.

The `loop()` function repeatedly switches the LED ON and OFF using delays to create a blinking pattern.

## 7. Testing and Results

The program was compiled and uploaded using PlatformIO.

The LED was tested to confirm that the blinking program operates correctly.

**Result:** Successful LED blinking was observed.

A screenshot of the working LED is included in the `screenshots` folder.

## 8. Version Control

Git was used to track changes, while GitHub was used to store and submit the project.

The final submission commit message is:

`FINAL: my blink`

## 9. Learning Outcomes

Through this exercise, I learned how to:

- Configure PlatformIO in Visual Studio Code.
- Program an ESP32-S3 using the Arduino framework.
- Compile and upload firmware.
- Troubleshoot configuration errors.
- Use Git commands to commit and push project changes to GitHub.

## 10. Conclusion

This exercise provided practical experience in embedded programming and microcontroller development. I successfully implemented and tested an LED blinking program using the ESP32-S3 and PlatformIO.

The project improved my understanding of embedded systems, hardware interaction and version control.