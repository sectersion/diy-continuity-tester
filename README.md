# diy-continuity-tester

### Why I made this
I needed to learn to solder so I made this project. It runs power through one lead and the other lead expects it, and that activates a buzzer and an LED to signal an electrical connection. 

The solder quality isn't the best, but I learned how to use my iron so I consider it a success.

---

### Pictures
<img width="1920" height="1080" alt="External View" src="https://github.com/user-attachments/assets/c72152b4-d51c-4789-9c97-2a7d1732b533" />
<img width="1920" height="1080" alt="Internal Wiring" src="https://github.com/user-attachments/assets/072da00e-f8c8-4a95-8462-21b52bd3bb59" />

---
## BOM

This project is pretty simple to build. You need a:
 - perfboard
 - male to male jumper wires
 - 5v buzzer
 - 220R resistor
 - LED (any color, i used red)

Most of these parts can be found in "microcontroller starter kits" if you want to buy them all at once.

---

### How it works
I designed a wiring diagram to explain better how this project works.

<img width="1152" height="648" alt="wiringdiagram" src="https://github.com/user-attachments/assets/2939b6ab-bc4d-4748-ac7e-22bc5155434c" />

The probes are an analog to the probes on a multimeter. One probe is tied directly to the voltage source, so it is always high. I am calling this the output probe. 

The other probe is the input probe, and it is connected to the positive pin of a buzzer and a 220R resistor. The resistor is connected to an LED, and the LED and negative pin of the buzzer are connected to ground. 

In practice, the effect of this is when the two probes are electrically connected (like a multimeter continuity tester) the buzzer will beep and the LED will flash.

*Sorry for the bad quality photos, that's the only camera I have.*
