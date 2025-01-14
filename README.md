# LED Arcade Game 🎮

## **Objective**
The LED Arcade Game challenges players to test their timing skills by pressing a button when the red LED matches the green LEDs. The game features six progressively difficult levels, requiring precision and focus as the difficulty increases.

---

## **Technology Stack**
- **Programming Language**: C++
- **Hardware**: 
  - Arduino microcontroller
  - LEDs (Red and Green)
  - Push-button

---

## **Features**
- **Dynamic LED Patterns**: LEDs illuminate in dynamic sequences to keep players engaged.
- **Progressive Difficulty**: Six levels of increasing challenge to test reaction times and focus.
- **Interactive Gameplay**: Immediate feedback when the button is pressed, making the game engaging and competitive.

---

## **How It Works**
1. **Setup**: 
   - The game starts with a simple LED pattern on Level 1.
   - A red LED moves across the green LEDs in a sequence.

2. **Gameplay**:
   - Players must press the button at the exact moment when the red LED aligns with one of the green LEDs.
   - If the timing is correct, the player advances to the next level.

3. **Challenge**:
   - Each level speeds up the LED pattern, making it harder to match the timing.

---

## **Hardware Setup**
### **Components Needed**
- 1 x Arduino (e.g., Arduino Uno or Nano)
- 6 x Green LEDs
- 1 x Red LED
- 7 x Resistors (appropriate values for LEDs, typically 220Ω)
- 1 x Push-button
- Jumper wires
- Breadboard

### **Wiring Diagram**
- Connect the **green LEDs** and **red LED** to digital pins on the Arduino.
- Attach the push-button to another digital pin, with a pull-down resistor for stable input.
- Power the LEDs via the Arduino with appropriate resistors.
