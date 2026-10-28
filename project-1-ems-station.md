---
layout: default
title: "Project 1: EMS Station"
---

# Project 1: EMS Station

1. Project Overview

I build an EMS station using a microbit controller and the hummingbird kit connected to the computer. The traffic light should flash yellow when an emergency is initiated, cars should stop moving and a garage door should open for emergency vehicles.

Planning & Design
I planned to make a garage door so it can open when there are emergencies for vehicles to come out.



Here's a picture of me hooking up the microbit controller to the computer! we used batteries to power it (provided by Mr Davisson)

<img width="828" height="828" alt="image" src="https://github.com/user-attachments/assets/462c4ee3-6818-43a9-b671-ca3c6b244e65" />

Another picture of me, testing out the green light after connecting it into the slots.

<img width="804" height="770" alt="image" src="https://github.com/user-attachments/assets/7463ee2b-580d-4774-a267-6ea21a33eca9" />


Here's my early sketch. The arch being opened when an emergency is happening.
<img width="517" height="385" alt="Screenshot 2026-10-27 201400" src="https://github.com/user-attachments/assets/38bbf26d-f0e2-407f-9cc1-02a999ea6537" />



Alonzo Sprite code and description:
<img width="1054" height="657" alt="image" src="https://github.com/user-attachments/assets/d65f4f21-d187-4ef4-aeaa-7ba0d01cac05" />
This is the code for Alonzo. Here's what the coding blocks mean. when space key pressed: Connects the software to Hummingbird Port A so the computer can talk to the robot. when green flag clicked (Setup): Resets Alonzo to 75% size, teleports him to the center, flips him 180 degrees, switches to his starting costume, and broadcasts ready for emergency to prime the game. when green flag clicked (Movement): Runs a forever loop that forces Alonzo to follow your mouse pointer so you can steer him around the map. when the green flag clicked (Sound Reaction): Continuously checks the physical sound sensor. If ambient noise goes over 30, it spins Position Servo 1 to 90 degrees. when I receive emergency: Loops a two-tone alarm (Note 71 and Note 70) repeatedly until Alonzo's costume switches back to costume #1.

Incident Sprite code and description:
<img width="1222" height="624" alt="image" src="https://github.com/user-attachments/assets/363ef940-2e28-4037-9347-755081583c16" />
Medical: Switches costume to hurtscratchscat 
<img width="1219" height="631" alt="image" src="https://github.com/user-attachments/assets/89cc8b31-b112-4fc0-a787-f71e5b0391aa" />
Fire: Switches costume to firescratchcat
<img width="1219" height="409" alt="image" src="https://github.com/user-attachments/assets/aba441ad-3bec-4756-8354-93f4d9a66c68" />
Tree: Switches costume to catuptree

On start, they switch to these costumes and shrink to 35% of their size. Then wait until Alonzo touches them and verifies if Alonzo is in his original form.
When they are touched if Alonzo is in his original form, they broadcast emergency and activate the emergency lights/buzzer lights. and tell Alonzo to switch into the matching costume.

<img width="197" height="233" alt="image" src="https://github.com/user-attachments/assets/ffd0fd3d-2bef-4056-a329-85df89e13881" />


for example, by dragging Alonzo over the fire incident, it changes him into a firefighter outfit, like in the screenshot.

Stage description:
<img width="1222" height="616" alt="image" src="https://github.com/user-attachments/assets/6a7672d8-73f9-4240-a486-6c26ef0507b7" />
The Stage handles how the physical LEDs, Servos, and Sensors interact with the environment:

Sound activated lights: If the Sound Sensor value is greater than 20 then LED 1 (yellow light) ON and LED 2 (green light) OFF. If the value for the Sound Sensor is less than or equal to 20 then LED 1 (yellow light) OFF and LED 2 (green light) ON.

Emergency Flashers: When emergency broadcast is heard, a sequenced script toggles on yellow light and green light to manage traffic during the emergency.

Safe reset: When space is pressed, it will reset all the lights and kills power to the led lights causing them to turn off.



Problem I ran into: for the light of my traffic light, I put the yellow and green cables in the wrong places.
I solved this problem by switching my wire from my G spot to my B spot and my B spot wire to my G spot wire.


Final thoughts/Reflection.

Im proud of my code final product and how it turned out.
Sadly, we did not get to finish the garage door because there was not enough time for the class.
