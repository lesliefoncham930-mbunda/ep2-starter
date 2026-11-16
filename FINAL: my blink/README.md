# EP2 – ESP32-S3 LED Blinking Project

**Student:** Leslie Mbunda  
**Project:** EP2 – Embedded Programming  
**Platform:** PlatformIO  
**Development Board:** ESP32-S3 DevKitC-1  
**Framework:** Arduino

## 1. Project Overview

This project demonstrates LED control using an ESP32-S3 development board and PlatformIO in Visual Studio Code.

The main objective was to configure the development environment, write an LED blinking program, upload the firmware to the board and verify that the LED operates correctly.

## 2. Project Objectives

- Set up Visual Studio Code and PlatformIO.
- Configure an ESP32-S3 development board.
- Understand the purpose of the `platformio.ini` configuration file.
- Write and upload an LED blinking program.
- Test and verify the LED functionality.
- Use Git and GitHub for version control and project submission.

## 3. Hardware and Software Requirements

### Hardware
- ESP32-S3 DevKitC-1 development board.
- USB cable.
- LED (if using an external LED).
- Resistor (if using an external LED).

### Software
- Visual Studio Code.
- PlatformIO IDE extension.
- Arduino framework.
- Git and GitHub.

## 4. Project Structure

```text
ep2-starter/
│
├── platformio.ini
├── README.md
│
├── src/
│   └── main.cpp
│
├── examples/
│   └── session01_plain_led.cpp
│
└── screenshots/
    └── my-blink.png
```

## 5. PlatformIO Configuration

The `platformio.ini` file contains the project configuration.

It specifies:
- The target development board.
- The ESP32 development platform.
- The Arduino framework.
- Serial monitor speed.
- Upload configuration and build flags.

## 6. LED Blinking Implementation

The LED blinking program is implemented in `src/main.cpp`.

The program initializes the LED pin and continuously switches the LED ON and OFF using timing delays.

The `setup()` function initializes the hardware and serial communication, while the `loop()` function executes the blinking pattern repeatedly.

## 7. Testing and Results

The firmware was compiled and uploaded using PlatformIO.

The LED was tested to verify that the program operates as expected.

**Result:** Successful LED blinking was observed.

A screenshot demonstrating the working LED is included in the `screenshots` folder.

## 8. Git and GitHub

Git was used to track project changes and GitHub was used to store and submit the project.

The final submission commit is:

`FINAL: my blink`

## 9. What I Learned

Through this exercise, I learned how to configure PlatformIO, work with an ESP32-S3 development board, write and upload Arduino firmware, troubleshoot configuration errors and manage project files using Git and GitHub.

I also gained practical experience with embedded programming and hardware testing.

## 10. Conclusion

The EP2 exercise provided practical experience in embedded systems development. I successfully configured my development environment, implemented an LED blinking program and tested its functionality.

This project helped strengthen my understanding of microcontroller programming, PlatformIO and version control.
