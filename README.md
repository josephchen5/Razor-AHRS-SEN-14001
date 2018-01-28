# Razor AHRS SEN-14001

All credit goes to the original coder found here: https://github.com/Razor-AHRS/razor-9dof-ahrs

All I did was change a few lines of code, the board orientation, and added some running filters.  I have also added some python scripts to visualize the YPR using PyQT, so be sure to download the correct Python Libraries if you want to use this graph.

Im new to GitHub so please forgive me if something doesnt work or I havnt given proper acknowledgement or credit.

The code seems to work very well once the magnetometer is calibrated but I'm sure there are some improvements that can be made.  With that said, please feel free to make improvements or suggestions and  I will try to answer any questions that you have.


-> $ ls -l /dev|grep ttyACM
-> $ sudo cp razor_imu_9dof.rules /etc/udev/rules.d    " razor_imu_9dof "
// serial port baud rate  Razor_AHRS.ino  #define OUTPUT__BAUD_RATE 57600

Sensor calibration  Razor-AHRS Tutorial https://github.com/Razor-AHRS/razor-9dof-ahrs/wiki/Tutorial

