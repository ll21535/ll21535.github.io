Project 2: Railroad Crossing


**Team Members:** [Your Name(s)]  
**Hardware:** BBC micro:bit + BirdBrain Hummingbird Bit Robotics Kit  
**Software:** Snap!

---

## Project Overview
* **What we are building:** [Describe your robot or interactive device, e.g., an automated cardboard gate/creature].
* **What it should do:** [Explain the main goal and behavior, e.g., when someone approaches the distance sensor, the LED changes color and the servos move].

---

## Planning & Design
[Insert pictures of your initial sketches or wiring diagrams here]

* **Design Decisions:** [Explain why you chose specific materials, sensor placements, or servo mechanisms].
* **Component Layout:**
  * **Sensor Port [1/2/3]:** Ultrasonic Distance Sensor
  * **Tri-Color LED Port [1/2]:** Status indicator light
  * **Servo Port [1/2/3/4]:** [Describe what each servo controls]

---

## Build Process
### Step 1: [e.g., Cardboard Base & Mounting]
[Insert progress photo/video]  
*Caption: [Explain what you built or wired in this step].*

### Step 2: [e.g., Wiring the Hummingbird Bit]
[Insert progress photo/video]  
*Caption: [Explain how you connected the sensors, LEDs, and battery pack].*

---

## Code
[Insert screenshots of your main Snap! script blocks here]

* **How the Code Works:** [Walk through the logic of your blocks—explain loops, `if/else` conditions, and sensor thresholds].

### Snap! Project Link
* **[Click here to view our live Snap! Program]([Paste your working, shared Snap! URL here])**

---

## How It Works
* **Inputs (Sensors):** [Explain what data the ultrasonic distance sensor or micro:bit buttons collect].
* **Processing (Code/Decisions):** [Explain how the Snap! code evaluates the sensor values to make decisions].
* **Outputs (Lights, Servos, etc.):** [Explain how the Tri-Color LED and servo motors react].

### System Timetable / Sequence

| Time / Trigger | Input State | System Action (Output) |
| :--- | :--- | :--- |
| **0s (Idle)** | Distance > [X] cm | LED glows [Color]; Servos stay at [Angle]°. |
| **Trigger** | Distance < [X] cm | LED changes to [Color]; Servo 1 rotates to [Angle]°. |
| **+2 seconds** | Timer elapsed | Servo 2 moves to [Angle]°; system resets. |

---

## Testing & Debugging
1. **Problem 1:** [Describe the first issue, e.g., servo jittering or distance sensor reading inaccurate numbers].
   * **What we tried:** [Explain the fix you attempted, e.g., checking battery voltage or adjusting the `wait` block].
   * **What happened:** [Describe the outcome].

2. **Problem 2:** [Describe the second issue, e.g., Tri-Color LED not lighting up].
   * **What we tried:** [Explain the fix you attempted, e.g., verifying R, G, B wires were firmly in the terminal blocks].
   * **What happened:** [Describe the outcome].

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
