# BITalino R-IoT firmware - Logging version

Slight changes to version 2.041 of the BITalino R-IoT original firmware in order to send the collected IMU data through the serial port - UART protocol. Original firware can be found [here](https://github.com/BITalinoWorld/firmware-bitalino-riot).

For the amount of printed data, in this version the maximum sampling frequency is 100 Hz (which corresponds to a minimum period of 10 ms). The larger the amount of data to print, the lower has to be the sampling frequency.

In the used setup the DataLogger used was the following: [SparkFun OpenLog](https://learn.sparkfun.com/tutorials/openlog-hookup-guide#firmware).
As for the firmware, the [SparkFun Minimal firmware](https://github.com/sparkfun/OpenLog/blob/master/firmware/OpenLog_Firmware/OpenLog_Minimal/OpenLog_Minimal.ino) was used.

NOTE: The sampling frequency of the data collection must be matched to the R-IoT base sampling frequency so that the recorded data is correct

#### credits

This change was made following a dissertation developed at Instituto de Telecomunicações of Instituto Superior Técnico in the area of biomechanics associated with the practice of swimming.
This thesis is led by teachers Paulo Lobato Correia and Hugo Silva.

Author: Eduardo Félix - [linkedin.com/in/eduardofrfelix](https://www.linkedin.com/in/eduardofrfelix/)