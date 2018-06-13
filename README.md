# BITalino R-IoT Firmware Adapted for Data Logging

## Overview

Slight changes to version 2.041 of the BITalino R-IoT original firmware in order to send the collected IMU data through the serial port (UART) to enable data logging. The original firmware can be found [here](https://github.com/BITalinoWorld/firmware-bitalino-riot).

For the amount of printed data in this version, the maximum sampling rate is 100 Hz (which corresponds to a minimum period of 10 ms). The larger the amount of data to print, the lower has to be the sampling frequency.

This configuration has been tested for the [SparkFun OpenLog](https://learn.sparkfun.com/tutorials/openlog-hookup-guide) block running the [SparkFun Minimal firmware](https://github.com/sparkfun/OpenLog/blob/master/firmware/OpenLog_Firmware/OpenLog_Minimal/OpenLog_Minimal.ino).

NOTE: The sampling frequency of the data collection must be matched to the R-IoT base sampling frequency so that the recorded data is correct

## Acknowledgements

This change was made following a dissertation developed at the IT - Instituto de Telecomunicações of Instituto Superior Técnico in the area of biomechanics associated with the practice of swimming, under the supervision of Prof. Paulo Lobato Correia and Prof. Hugo Plácido da Silva.

## Author
Eduardo Félix - [linkedin.com/in/eduardofrfelix](https://www.linkedin.com/in/eduardofrfelix/)
