
# Washing Machine Motor – Forward/Reverse Control

This project demonstrates a classic control and power circuit built in **CADe SIMU** for operating a washing machine motor.  
The motor performs **alternating forward and reverse motion**, controlled using timers and interlocking logic.

---

## ⚡ Project Overview

The circuit simulates the washing machine drum rotation by switching between:
1. **Forward rotation – 5 seconds**
2. **Stop**
3. **Reverse rotation – 5 seconds**
4. **Stop**
5. Repeats continuously

Both the power circuit and the control circuit are implemented.

---

## 🔌 Power Circuit Components
- 3-phase motor
- Circuit breakers (protection)
- Overload relay (OL)
- Forward/Reverse contactors
- 3-phase power connection to the motor

---

## 🧠 Control Circuit Logic
- **Timers** used to define the 5-second forward and reverse periods  
- **Interlocking** between forward and reverse contactors to prevent short circuits  
- **Relays** to latch signals and sequence operations  
- **Overload trip** integrated into the control line for motor protection  

---

## 🗂️ Files Included
- `code/` → CADe SIMU diagram file for the entire circuit  
- `media/` → Screenshots of the implemented circuit

---

## ✔️ Skills Demonstrated
- Forward/reverse control logic  
- Classic control sequencing  
- Timer application  
- Motor protection circuits  
- Power wiring in 3-phase systems  
