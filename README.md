- 👋 Hi, I’m @chester2400
- 👀 I’m interested in developing a cruise control.
- 🌱 I’m currently learning c++
- you can back me up with a donation via paypal on chester240.mk@gmail.com


Here I will add code scematics and all usefull data to build cruise control.
I will update the files whenever I have time.
If you have any questions concerning thiss build please feel free to ask.
The whole device consists of couple of elements:
- main unit with arduino 2560 pro mini, bluetooth module, optional oled screen and a min 6A ubec to power the servomotor.
- servo motor to control the throttle.
- dispay unit with arduino nano every (plain nano didnt have inaf memory for the whole program), oled display, and 5 RGB LED's (this unit is optional and not necesery for the cruise control funcionality but at this moment at least one oled screen is necesary to setup and tune PID's).
- quickshifter sensor swich (also optional).
- 3 button unit, 2 momentary pushbuttons and one on/off to power the main unit and to turn it off in case of emengancy.
- 2 led's to indicate operation ( I used buttons with build in leds)
At this moment the quickshifter is a plain relay thut cuts power to fuel injectors. I have plans to replace it with solid state mosfets to to control the power for the incetors or ignition coils in case of the carburated.
/n more information on the wiring and pitures soon.



<!---
chester2400/chester2400 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
