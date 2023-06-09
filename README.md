# MiltonMoon
This is code written to sync the Uncle Milton Moon In My Room lamp to real moon phases by replacing the original micro controller with an Arduino.

I leveraged a Seeed XIAO. Connect the light’s LEDs to pins 1-6, connect the switch to pin 8. When the switch is on, the light will run in “Fast Mode”, changing phases every two seconds. This can be used to sync the light to the moon, or leave it in fast mode for ambiance. Turn “Fast Mode” off to change phases with the moon. The code is divided in to 12 phases. The light will progress one phase every 58 hours. This should approximately track with the moon, but may drift over time due to rounding. Power the lamp with the Arduino to avoid wasting batteries.  

 

 
