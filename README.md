Scope of functionalities
This project has the following functionalities:
Setting a new password: The user can enter a new password using the keypad and confirm it by pressing ‘#’.

The password should be 5 digits long and should not start with ‘#’.

If the password is valid, it is saved in the EEPROM memory and a confirmation message is displayed on the LCD screen.
If the password is invalid, an error message is displayed and the user can try again.
Locking and unlocking the door:

The user can lock or unlock the door by entering the correct password and pressing ‘#’.
If the password is correct, the DC motor rotates clockwise or anti-clockwise to lock or unlock the door respectively, and a success message is displayed on the LCD screen.
If the password is incorrect, a failure message is displayed and the buzzer sounds for one second.
User has three attempts to enter the correct password before the system is blocked for one minute.
