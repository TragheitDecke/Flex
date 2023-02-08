# Flex
Arduino Flex
This program will sample a 50-150hz signal depending on ethanol 
content, and output a 0-5V signal via PWM.
The LCD (for those using an Arduino Uno + LCD shield) will display ethanol content, hz input, mv output, fuel temp

Connect PWM output to Output. 3.3kOhm resistor works fine.

Input pin 8 (PB0) ICP1 on Atmega328
Output pin 3 or 11
