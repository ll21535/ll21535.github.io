Project 2: Railroad Crossing


By Leon L


**Hardware:** micro:bit + BirdBrain Hummingbird Bit Robotics Kit  
**Software:** Snap!

---

## Project Overview
* **What we are building:**
* 
* **What it should do:** [Explain the main goal and behavior, e.g., when someone approaches the distance sensor, the LED changes color and the servos move].

---

## Planning & Design
<img width="896" height="1189" alt="image_fa06b0a8" src="https://github.com/user-attachments/assets/f3143209-7ca9-4f54-9bf0-4f4d5a70f883" />
An early sketch of what I have planned, you can see the servo being used as a stop gate in this situation moving to a different position so it serves as a traffic light almost but for trains.


---

## Build Process
<img width="574" height="748" alt="image" src="https://github.com/user-attachments/assets/6e85fc9b-e057-4668-b29b-76180b91bcb5" />
I used a small piece of cardboard as it's purpose is to be the sign that moves position to position.


<img width="856" height="756" alt="image" src="https://github.com/user-attachments/assets/0f79617b-d4f7-4948-af9b-1a19590c3a70" />
Plugged the light in

## Code
<img width="992" height="609" alt="image" src="https://github.com/user-attachments/assets/78d6becb-fdc6-4b4a-981f-56aece5c4380" />
Code description: when you press the spacebar, it connects your robot, and there's a little floating block at the top that just shows how far away things are from your sensor so you can test it. Once you hit the green flag, the main loop starts watching the distance sensor, and if a train gets closer than 15 centimeters, it saves the date, time, and speed to a list, drops the crossing gate down to 90 degrees and makes the light flash red while playing a warning beep. When the train isn't there, it lifts the gate back up to 0 degrees. 

### Snap! Project Link
* **[Click here to view our live Snap! Program]([Paste your working, shared Snap! URL here])**

---

## How It Works
When a train comes by, the sensor would detect it and initiate the crossing activation. Which positions the servo to move the sign 90 degrees and flashes the light red for 2.5 seconds to let "pedestrians" walk by. It also plays a kind of loud note that lets people know it is available to walk.


---

## Testing & Debugging
The train

---

## Final Product
[Insert photos of the finished build]

* **Demonstration Video:** [Insert link to your demo video or upload directly to GitHub]
* **Summary of Final State:** [Note everything that works properly. If anything is unfinished or broken, clearly explain what you accomplished, what went wrong, and what remains to be done].

---

## Reflection
* **What I learned:** [Key takeaways about robotics, wiring, or Snap! programming].
* **What was challenging:** [The hardest part of the build or coding process].
* **What I would improve:** [One thing you would change with more time or materials].
* **My personal contribution:** [Specific tasks you handled, such as wiring, cardboard engineering, coding, or documentation].
