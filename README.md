# SW-MCU-STM32-I2CTest-004

Here is an I2C for SHT4X humidity and temperature sensor for STM32 microcontrollers.

![start](https://github.com/user-attachments/assets/b4a2711f-6719-4c9e-8f67-cfdb7abcaabf)

I generate code from its datasheet.

![meas](https://github.com/user-attachments/assets/3bd7e740-505a-4c8b-99b4-c8c5b1f87079)


![hum](https://github.com/user-attachments/assets/e4aa9e43-7b7d-49a6-b51f-a19a9ca8eb55)


![temp](https://github.com/user-attachments/assets/c9af00bd-d5dd-4603-85d8-044d73a880d4)


Added some debug prints, sometimes jumper wires can be loose connection.

If you manufacture PCB, you can remove those lines.

Added CRC to be sure data is received correctly from the sensor.

Measured 100 times and took average of it for better accuracy.

If there is any error for CRC, that's removed from calculation.

Displays on 0.96 inch LCD.

SHT40 has 0.2 Celsius , SHT45 has 0.1 Celsius accuracy. You can use it for various applications.

Hope this helps you,

Ceyhun Pempeci STM32 I2C
