# 4-Digit-Digital-Lock-using-Arduino
This project is a 4-digit digital lock implemented using an Arduino Uno, 4x4 keypad, 16x2 LCD, and servo motor. The lock system allows users to enter a predefined PIN using the keypad. If the correct PIN is entered, the servo motor unlocks the system; otherwise, a buzzer alerts for incorrect attempts.

Components Used
<> Arduino Uno (Microcontroller)
<> 4x4 Keypad (for PIN entry)
<> 16x2 LCD Display (to show input and status)
<> Servo Motor (for locking/unlocking)
<> Buzzer (for incorrect PIN alert)
<> NPN Transistor (to drive the buzzer)
<> Resistors & Wires (for connections)
<> Breadboard (for circuit assembly)
Working Principle
The user enters a 4-digit PIN using the keypad.
The LCD display shows the entered PIN.
If the entered PIN matches the pre-defined PIN:
✅ The servo motor rotates, unlocking the system.
✅ The LCD displays a success message.
If the PIN is incorrect:
❌ The buzzer sounds as an alert.
❌ The LCD displays an error message.
The system allows multiple attempts and can be reset.
Circuit Connections
Keypad → Connected to Arduino D1-D7 pins 
LCD Display → Connected via Arduino A0-A5 pins 
Servo Motor → Signal wire connected to D9
Buzzer → Controlled using an NPN transistor, connected to D8
How to Use
Power the system using USB or external power supply.
Enter the 4-digit PIN using the keypad. which is (4 5 6 7) you can change this in code.
If the PIN is correct, the servo unlocks the system. 
If the PIN is incorrect, the buzzer sounds an alert.
Reset or re-enter the PIN to try again.
Applications
✅ Home & office digital door locks
✅ Safe security systems
✅ Industrial equipment locking

