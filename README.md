# SW-MCU-STM32-I2CTest-004

Here is an I2C for SHT4X humidity and temperature sensor for STM32 microcontrollers.

![start](https://github.com/user-attachments/assets/da9c88ee-c23d-4dfe-a70b-0f3b38288588)


I generate code from its datasheet.


![meas](https://github.com/user-attachments/assets/29613be2-c60a-4bce-af2e-f507d6ab7447)


![temp](https://github.com/user-attachments/assets/34a0751d-da62-4db1-abc4-17fe42f87cf4)


![hum](https://github.com/user-attachments/assets/47d8cdfb-cffe-41eb-adc1-c8c53a0609c6)




Added some debug prints, sometimes jumper wires can be loose connection.
If you manufacture PCB, you can remove those.

Added CRC to be sure data is received correctly from the sensor.

Measured 100 times and took average of it for better accuracy.

If there is any error for CRC, that's removed from calculation.

Displays on 0.96 inch LCD.

SHT40 has 0.2 Celsius , SHT45 has 0.1 Celsius accuracy. You can use it for various applications.

Hope this helps you,

Ceyhun Pempeci STM32 I2C
