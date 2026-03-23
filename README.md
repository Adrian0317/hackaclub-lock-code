# Servo Door Lock

This project uses a servo motor that physically moves a door lock. The servo will be turning left and right when powered, but the power is connected by a button instead of code.

 It works like

- When the button is pressed, the servo is powered and starts rotating back and forth, moving the lock mechanism.  
- When the button is released, power is cut and the servo stops, leaving the lock in its current position.

Hardware

- Servo motor  
- Door lock latch  
- 9v battery  
- Button (push‑to‑press)  
- Arduino

How it works

- The servo is wired so that it runs continuously when power is present.  
- The button is placed in the power line to the servo:
  - Button pressed → servo gets power → servo keeps rotating and moves the lock.  
  - Button released → power is cut → servo stops.  
- You design the mechanical linkage so that:
  - One stop position = **locked**  
  - The other stop position = **unlocked**
 
## Safety notes

- Make sure the servo can’t jam or force the lock too hard; add a small mechanical stop if needed.  
- Test with hand power first to see which direction locks vs unlocks.  
- You can later add an Arduino to control the button automatically (for example, with a web command or app).
