# F4-ESC-FC-stack
I designed my own F4 stack (not from scratch), made way too many mistakes I probably didn't notice. STM32F405GT6 as the main processor, and STMG071 as the ESC processors, AT765E OSD, ICM-20689 Gyroscope, Barometer, and a lot more wired with blood, sweat and tears.

This repository isn't for the world to see, but for that kid who thought he couldn't, the one who spent hours flying his drone, the one who stared at the PCB of PC's and his Arduino board, amazed and in awe. This is for that kid, to tell him that he finally did it, it isn't beautiful, and the chances it works are pretty low, it probably will make a true electrical engineer rage with the anger of a thousand suns, but atleast all the wires are connected, and he tried his best.

Hi, I'm Upkirat, and this is my F4 ESC+FC stack combo, a project I initially started in November 2024, but always postponed it, because I just didn't understand it. Jumping from plugging in designated wires to my Arduino, to designing my own PCB for a DRONE, wasn't the easiest transition I would say. I didn't give myself a chance to slowly ease into this field, rather I tried to explore as much knowledge was available, figuring out different parts, and if AI wasn't there to help me, this would still be a project collecting dust on my TO-DO list. 

For this design I would definately not take credit for coming up with it, instead I relied mainly on 2 repositories here on GitHub, understoof them, recreated them, and hopefully made something that made sense.

#For my FC inspiration -
https://github.com/PoplavskyiB/Sowa_FC

#For my ESC inspiration - 
https://github.com/crteensy/ESC_4in1_G071_1S3_SIZ200

these designs help me understand the different components, the process, and basically guided me on this process. My greatest challenge with this project wasn't the wiring, the PCB design or anything else, but it was simply learning what made a flight controller and ESC for a drone, what all did it need, what features, how does it function, WHY does it function, as this isn't something being done for the first time, countless companies have made so many versions that are way better (because they were made by someone who actually knows how this stuff works). 

But for me, whatever the result was for this, I know that I have learned, I have worked hard, and I am proud of my result...so here it is
<img width="1302" height="994" alt="image" src="https://github.com/user-attachments/assets/8f4d5006-c5e1-40e7-a41e-fa3f90e146a7" />

<img width="1273" height="925" alt="image" src="https://github.com/user-attachments/assets/baaa9162-f227-4ec7-b97e-d7350334cb01" />

This PCB was challenging, as it was the progress of multiple stages, of multiple iterations, too many times restarting the same project, getting stuck at the same time. At the start of this project I didn't know the purpose of a capacitor or what is a pull-down or pull-up resistor, but YouTube, ChatGPT, Github and datasheets helped me understand something that I barely understood.

<img width="1044" height="849" alt="image" src="https://github.com/user-attachments/assets/20941a65-4842-40ed-9be2-4dfd66668d10" />
<img width="1208" height="796" alt="image" src="https://github.com/user-attachments/assets/6d19adde-b985-42d6-a24c-4f6e87032a41" />

One unique thing you may notice with my ESC is that every corner or cluster for each motor is designed differently, this isn't out of laziness or forgetfullness but me challenging myself. I wanted to start each design off the same base but I wanted to challenge myself by wiring them all individually, without repeating the same design. For a actual product this is probably not a smart decision, but for this personal project of mine this was something I did to challenge myself. Seeing how every corner can be so uniqely made, it was more of a mental challenge of organizing all these things myself.

Also just for comparison of how far I have come through my designs this is the TRUE V1 of my FC, where the mindset was shove it in and make it fit basically.
<img width="1225" height="1027" alt="image" src="https://github.com/user-attachments/assets/daf2f317-890f-426a-9dc8-d89235f5bcd1" />

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

#My FC progress
<img width="971" height="1080" alt="image" src="https://github.com/user-attachments/assets/04cdad2b-bc52-463e-8d9c-6c5a6d2bec5d" />
<img width="1112" height="1012" alt="image" src="https://github.com/user-attachments/assets/94d0ee96-282a-425b-af79-13f56d218579" />
<img width="1162" height="1042" alt="image" src="https://github.com/user-attachments/assets/b32a75c8-662e-40a1-b8f9-acaa46c7ff6f" />
<img width="1081" height="985" alt="image" src="https://github.com/user-attachments/assets/b993046c-6391-423d-aaf4-66dc8583238e" />


#My ESC progress
<img width="942" height="942" alt="image" src="https://github.com/user-attachments/assets/c775cc9c-2e51-476d-8a69-e4046cb0b531" />
<img width="1265" height="973" alt="image" src="https://github.com/user-attachments/assets/f32a8767-b6bc-4bd4-978b-5a51af9d353d" />
<img width="1352" height="1095" alt="image" src="https://github.com/user-attachments/assets/12a6ee51-b918-4f00-a0b8-eaafc78382a4" />
<img width="1107" height="990" alt="image" src="https://github.com/user-attachments/assets/bed23426-6be2-4485-89d2-8236c54dcacd" />


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Take my one advice for anyone trying to learn or get into this field, you aren't confused you are just uninformed, there is plenty of information available on the internet, and not everything has to be perfect on it's first try
This project is far from perfect, I doubt whether if this would actually work, I 100% expect this to catch fire the first time I plug it in, but from that I will learn, from that I will grow, and from that so will my passion.
