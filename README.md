- 👋 Hi, I’m @chester2400   chester240.mk@gmail.com
- 👀 I’m interested in developing a cruise control.
- you can back me up with a donation via paypal on https://paypal.me/chester240


Here I will add code scematics and all usefull data to build cruise control.  
I will update the files whenever I have time.  
-If you have any questions concerning thiss build please feel free to ask.  
-The whole device consists of couple of elements:
- main unit with arduino 2560 pro mini, bluetooth module, optional oled screen and a min 5A ubec or buck converter to power the servomotor at 6v.
- servo motor to control the throttle. I used savox sc-1251mg. If you use another make sure it turns freeley(no binding) with no power and have inaf torque.
- dispay unit with arduino nano every (plain nano didnt have inaf memory for the whole program), oled display, and 5 RGB LED's (this unit is optional and not necesery for the cruise control funcionality, some of the parameters of the cruise contol can now be tuned via serial monitor, for all options display is required.).
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
I'm curently working on a power suply for the servo to get rid of the UBC and have everything on the borad. (Update on that: Turns out a pain 5A buck coverter is motre then ianf so im puting the part on hold. I redesigned the board to be able to easy install the buck converter on the pcb.  
![New pcb](https://github.com/chester2400/chester2400/blob/main/pcb3d.jpg)
  
  
    
 
   
     
Here are new buttos for the cc. Ones I have tested them, I will upload the stl files. This design is for DL1000A but im sure it can be altered to fit any/most bikes.   
![New buttons](https://github.com/chester2400/chester2400/blob/main/buttos.jpg)    
![New buttons2](https://github.com/chester2400/chester2400/blob/main/buttons2.jpg)    
I have added new diagrams for new version.
  
  







I have diceded to offer the pcb's and servo mounting brackets to fund futher development. It will be 30 USD including shipping.  
Please send me an e-mail on chester240.mk@gmail.com with a specific bike you want me to design a mounting bracket.
I will update requests here.
Once inaf people will back me for a certain model i will buy a throttle body and make all happen.
  
  ![pcb assebeled](https://github.com/chester2400/chester2400/blob/main/IMG_4257.JPG)  
  

  
  
    
    https://youtu.be/o_2QjCjgXKo
      
    
      
        
    
      
      

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fchester2400%2Fchester2400&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)
<!---
chester2400/chester2400 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
