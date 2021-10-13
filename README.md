- 👋 Hi, I’m @chester2400
- 👀 I’m interested in developing a cruise control.
- 🌱 I’m currently learning c++
- you can back me up with a donation via paypal on chester240.mk@gmail.com


Here I will add code scematics and all usefull data to build cruise control.  
I will update the files whenever I have time.  
-If you have any questions concerning thiss build please feel free to ask.  
-The whole device consists of couple of elements:
- main unit with arduino 2560 pro mini, bluetooth module, optional oled screen and a min 5A ubec or buck converter to power the servomotor at 6v.
- servo motor to control the throttle. I used savox sc-1251mg. If you use another make sure it turns freeley(no binding) with no power and have inaf torque.
- dispay unit with arduino nano every (plain nano didnt have inaf memory for the whole program), oled display, and 5 RGB LED's (this unit is optional and not necesery for the cruise control funcionality but at this moment at least one oled screen is necesary to setup and tune PID's).
- quickshifter sensor swich (also optional).
- 3 button unit, 2 momentary pushbuttons and one on/off to power the main unit and to turn it off in case of emergancy.
- 2 led's to indicate operation ( I used buttons with build in leds)
At this moment the quickshifter is a plain relay that cuts power to fuel injectors. I have plans to replace it with solid state mosfets to to control the power for the injetors or ignition coils in case of the carburated bike.  
-more information on the wiring and pitures soon.  
Here is a prototype PCB with changes I made later.  
![Prototype pcb](https://github.com/chester2400/chester2400/blob/main/git1.jpeg)  
And here is the 3D printed main unit case and PCB.  
![Prototype pcb and case](https://github.com/chester2400/chester2400/blob/main/git2.jpeg)  
I have also designed an SMD board already assembled to fit over a standard arduino 2560 mega as a sheild, but since its not a comercial device i decided not to make it.  
If there are people that would be interested in that it is posible to make them.  

New update.  
I'm curently working on a power suply for the servo to get rid of the UBC and have everything on the borad.  

Here are new buttos for the cc. Ones I have tested them, I will upload the stl files. This design is for DL1000A but im sure it can be altered to fit any/most bikes.   
![New buttons](https://github.com/chester2400/chester2400/blob/main/buttos.jpg)    
![New buttons2](https://github.com/chester2400/chester2400/blob/main/buttons2.jpg)    
    
      
      

<!---
chester2400/chester2400 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
