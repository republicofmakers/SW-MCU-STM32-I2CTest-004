# SW-MCU-STM32-I2CTest-004

Here is an I2C for SHT4X humidity and temperature sensor for STM32 microcontrollers.

I generate code from its datasheet.

Added some debug prints, sometimes jumper wires can be loose connection.
If you manufacture PCB, you can remove those.

Added CRC to be sure data is received correctly from the sensor.

Measured 100 times and took average of it for better accuracy.

If there is any error for CRC, that's removed from calculation.

Displays on 0.96 inch LCD.

SHT40 has 0.2 Celsius , SHT45 has 0.1 Celsius accuracy. You can use it for various applications.

Hope this helps you,

Ceyhun Pempeci STM32 I2C
