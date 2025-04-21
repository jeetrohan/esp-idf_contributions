# aht20
I2C driver for Aosong AHT20 humidity and temperature sensor using esp-idf.
Tested with hardware.

# How To Use
This aht20 driver includes a demo example.
Please follow that for initialization and reading the sensor.
Other public APIs are documented in AHT20.h.

Additionaly, select AHT20 menu under Component Config menu in menuconfig or sdkconfig; to use CRC(default is not used)
or change the clock speed of device (deault is 100KHz).
![image](https://github.com/user-attachments/assets/fc8680fb-1567-477c-92f8-52dd126e6f9d)

Also, this aht20 driver has a test app. 
