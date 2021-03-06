#MPU-6050 Python

This program handles the I2C communication between a Raspberry Pi and a MPU-6050 Gyroscope/Accelerometer sensor.

For this program to work you need to have I2C enabled on your Raspberry Pi and you need to have the python-smbus package installed.

This project is available on pypi: https://pypi.python.org/pypi/mpu6050-raspberrypi/

#Installation

You can install this module by executing the following command:

    sudo pip install mpu6050-raspberrypi

#Usage

Using the module is quite straight-forward. You simply create an object of the
mpu6050 class and use the appropriate methods to get your data.

The following methods are available to read sensor data:

```python
get_accel_data()
get_gyro_data()
get_temp()
```

#License

This project is licensed under the MIT License. For the full license, please refer to the LICENSE file.
