A smart embedded safety system designed for women traveling in automobiles. The system sends an emergency SMS with live GPS location to a registered contact when the panic button is pressed and activates a buzzer alarm. The buzzer can be remotely turned off by replying with the SMS command **STOP**.

**Features**
-  One-button emergency alert
-  Live GPS location sharing
-  SMS alert using GSM module
-  Loud buzzer alarm
-  Remote buzzer OFF via SMS
-  Low-cost Arduino-based solution

  **Hardware Components**

- Arduino Uno
- SIM800L GSM Module
- NEO-6M GPS Module
- 16x2 I2C LCD Display
- Push Button
- Active Buzzer
- Power Supply

**Software Used**

- Arduino IDE
- Embedded C/C++
- SoftwareSerial Library
- LiquidCrystal_I2C Library

**SMS Format**

EMERGENCY ALERT!
Need Help!

Location:
https://maps.google.com/?q=latitude,longitude
