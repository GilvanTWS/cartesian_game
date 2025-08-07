# Cartesian Game 🎮💡

A Digital Circuits project developed for the **Digital Circuits** course in the **Computer Science** program at **Federal University of Cariri (UFCA)**.

## 🧠 Objective

Design and implement a digital game simulation using **Logisim ITA**, where a joystick controls a point in a **15x15 LED matrix**, with the current coordinates displayed in **7-segment displays**.

## 🔧 Technologies Used

- [Logisim ITA](https://logisim.altervista.org/): Digital logic simulator
- Combinational logic (Demultiplexers, Binary to 7-segment converters, Logic gates)
- Karnaugh Maps (for logic simplification)

## 🎮 Project Overview

- The player uses a digital **joystick** (with 4-bit X and Y outputs) to move a point (a lit LED) across a **15x15 matrix**.
- The X and Y coordinates of the active LED are **converted from binary to decimal** and displayed using **four 7-segment displays** (two for X and two for Y).
- The system ensures smooth and precise movement, allowing only one LED to be lit at a time.

## 🧩 Circuit Architecture

- **Demux Y**: Takes 4-bit input and activates one of the 15 matrix rows.
- **Demux X**: Built using 15 Demux Y modules, enabling selection of a specific column based on a second 4-bit input.
- **X and Y Displays**: Binary inputs are decoded and shown in decimal using combinational logic designed from **truth tables** and optimized using **Karnaugh Maps**.

## 👥 Authors

- Gilvan Alves Pastor Júnior  
- Gildo Alves de Lima Junior  

## 📅 Workflow & Development

- The project was built collaboratively, with **weekly online meetings** via Discord and WhatsApp.
- Tasks were divided, and constant testing ensured the project's success.
- Final validation was conducted by Professor **Ramon Nepomuceno** and teaching assistant **Fagner**, who approved the circuit's structure and functionality.

## ✅ Final Thoughts

This project allowed for practical application of digital logic concepts and helped reinforce the understanding of:

- Data flow in digital systems
- Modular circuit design
- Simulation and debugging in Logisim ITA
- Technical documentation and teamwork

**Cartesian Game** stands as a complete and interactive digital circuit system, showcasing the potential of logic-based design.

---
