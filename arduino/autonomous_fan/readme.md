This project was made for the 2024 IEEE technothon with a team of 3 total members. It is a prototype for an autonomous fan which is password protected,
and it automatically turns on when the difference between the desired room temperature you want and real temperature of the room
is some predefined value such as 3 degrees celcius. It will also automatically turn off as the difference between temperatures is 
less than our predefined threshold. 

It was implemented on an arduino UNO R3 microcontroller and attached to our arduino/circuit was a liquid chrystal lcd screen, 
an aht20 temperature sensor, a pc fan, a comparator op amp circuit, and a 4x4 membrane matrix keypad. The op amp circuit was used to
amplify our output voltage from one of the digital arduino pins to the correct voltage we needed to power the fan, since the pin voltage was limited
by our other components attached.