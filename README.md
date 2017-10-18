# Moon Phase Calculation
A simple algorithm to calculate moon phase on a date using an Arduino. The moon phase is shown on a Nokia 5110 display.

Author: TorLab

# Disclaimer

This code is directly inspired from : 
http://www.skyandtelescope.com/wp-content/observing-tools/moonphase/moon.html

I adapted the code for Arduino and used a monochrom display (NOKIA 5110) to show up moon phases.
The main function is moonPhases(int year, int month, int day) where 'year' is a four-digit number.
Although I tested the code (on Arduino Nano) for different dates, and the results were the same 
as those given by the original website, I provide this code without warranty.

Please note that the Bitmaps are for a black/white screen, so a pixel ON would match the unlit 
part of the moon while a pixel OFF matches the illuminated face. If you are using an OLED display, 
you should then invert pixels in the Bitmaps.

# Breadboard Circuit
[](MoonPhaseCalculation/images/breadboard circuit)

