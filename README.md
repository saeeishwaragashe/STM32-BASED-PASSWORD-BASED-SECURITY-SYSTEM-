# STM32-BASED-PASSWORD-BASED-SECURITY-SYSTEM-
STM32 BASED PASSWORD SECURITY SYSTEM :

HELLO ! This Project is for the STM32G071RB using the Arduino IDE. It interfaces with a 4x4 keypad and an LCD (16x2) to check a password and display "ACCESS GRANTED" or "ACCESS DENIED" based on the input.
Hardware Requirements:

STM32G071RB Nucleo Board
4x4 Keypad
Connect rows and columns to digital pins.
16x2 LCD Display
Use an I2C interface for simplicity.
Connections:

Keypad: Assign GPIO pins for the rows and columns.
LCD: Connect to I2C pins (SDA, SCL).

Connections:

Keypad:
Rows to STM32 pins (e.g., PA0, PA1, PA2, PA3)
Columns to STM32 pins (e.g., PA4, PA5, PA6, PA7)
LCD (I2C):
SDA to PB7
SCL to PB6
