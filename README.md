# GNOR
![Orange](docs/orange.jpg)
![Hull](docs/boathull.gif)
##### GNOR Description
The Great Navel Orange Race (GNOR) is an annual competition held at UCF every year for the second intro to engineering course. The project involves students building a boat, submarine, or other watercraft that autonomously carries an orange around the reflection pond.
The TI Innovation lab is providing students with TI microcontroller boards (MSP430f5529 LaunchPad, MSP-EXP432P401R LaunchPad) and sensors (TI Sensor Hub) for use in their watercrafts. These components empower students to control servos, provide signals for high power relays and ESCs, measure angle change relative to starting angle, look at accelerometer data, and more.
This repository provides everything needed to get started using these components. This includes example code, pinouts, and more. If you have any questions or are having trouble getting started, you can find help at the UCF Innovation Lab in ENGII room 112 9AM-10PM M-F and Saturday 10-5. 

##### Install Instructions
## Installing the Required Libraries

This project requires the following libraries:

- [WS2812_MSP432](https://github.com/UCFInnovationLab/WS2812_MSP432/releases)
- [WS2812_MSP430](https://github.com/UCFInnovationLab/WS2812_MSP430/releases)

### Recommended installation method

Install the libraries from the ZIP files provided on each repository’s **Releases** page. Using release ZIPs ensures you install a specific tested version of each library.

1. Open the Releases page for each library.
2. Download the latest recommended ZIP file.
3. In the Arduino IDE, go to **Sketch → Include Library → Add .ZIP Library...**
4. Select the downloaded ZIP file.
5. Repeat for the second library.
