# 🚦 Traffic Light Control System – PLC (Siemens TIA Portal)

## 📌 Project Overview

This project implements a **traffic light control system for a four-way intersection** using a **Siemens PLC** programmed in **Siemens TIA Portal**.
The system uses **timer-based sequencing combined with interlock logic** to ensure safe, reliable, and conflict-free traffic signal operation.

---

## 🚥 System Description

* Controls traffic signals for **four directions** (North, South, East, West).
* Each direction includes **Red, Yellow, and Green** signals.
* **Interlock conditions** prevent conflicting green signals between directions.
* Timers manage signal duration and transitions.
* Ensures fail-safe operation and repeatable traffic cycles.


---

## 🔄 Traffic Light Sequence

1. **North–South Green**, East–West Red
2. **North–South Yellow**, East–West Red
3. **All Red (Interlock Safety Delay)**
4. **East–West Green**, North–South Red
5. **East–West Yellow**, North–South Red
6. Cycle repeats continuously


