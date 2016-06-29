# lcd-echo

This program uses my LCD_i2c.py module to write from the terminal directly
to a simple character LCD.
This module has to be in the same directory as the lcd-echo program in order to
function correctly.

To get the i2c address of the LCD, it reads from the file "/etc/lcd-echo.conf"
This configuration file should be formatted in the following way:
```
    address = 0x27
    width = 16
    max_lines = 2
    backlight = True
    clear_time = 60
```
Please note that this configuration file will not be generated automatically.
