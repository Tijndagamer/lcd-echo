# lcd-echo

This program uses my LCD_i2c.py module to write from the terminal directly
to a simple character LCD.

To get the i2c address of the LCD, it reads from the file "~/config/lcd-echo.conf"
The first (and only) line of this file should be formatted in the following way:
```
    address = 0x27
```
Please note that this configuration file will not be automatically generated.
