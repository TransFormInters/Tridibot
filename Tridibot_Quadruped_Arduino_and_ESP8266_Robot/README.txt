Tridibot Quadruped Arduino and ESP8266 Robot by Konredus on Thingiverse: https://www.thingiverse.com/thing:3050870

Summary

Hellou makers!!! Here es @Konredus again.

To all of you who follow me on instagram, facebook or youtube...you know this amazing proyect that we made at 2017 and today i wanna share it with you.

So...to build this robot you will need:

--------------------- 3d Printed Parts -----------------

Quant - Description of the parts

1 - Top Case Part (I recommend that you print the outer part up and put a lot of support inside)
1 - Buttom case part (same recomendation as TOP CASE)
1 - Front Sphere printed with transparent filament
4 - Legs (I recommend printing the hole side down)
4 - Knee
8 - Servo cover parts

----------------------- Electronic Parts ------------------

Quant - Description of the electronic component

8 - Servomotors MG90s (the little black metalic servos)
NOT The SG90 blue platic servo because tridibot is too heavy for them

1 - Arduino Nano (can use compatible CH340)
1 - Esp8266 -12f (version)
3 - 18650 Batteries
1 - On/Off switch
1 - Battery charge PLUG (this depends off your battery charger)
1 - 3S BMS power and charge control for the batteries
1 - Step Down to lover the 12v from the batteries to 5V
1 - LM317 to reduce te 5v from step down to 3,3v for the ESP
We use the LM317, because sometime we need to increase the ESP voltage to 3,5v.
That is because when the servos move all together, the voltage variate a lot and the ESP reset itself

Some extra capacitors to be able to stabilize the tensión
1 - NeoPixel Ring - 8 x WS2812 5050 RGB LED

------------------- Here The first version of PCB Board -------------

https://easyeda.com/Konredus/Tridibot_1-945e6290ff6c4314a4d4d2029378f218

Please i recommend to check it because it is still our first BETA versión os the PCB Board

------------------------ Code and instructions -----------------

https://github.com/andih256/Tridibot

And thats all!

Stay tuned and follow me on Instagram.

Goodbye makers! :D
