#🔋 Smart Microgrid Simulation with Solar PV – Simulink Model

This project simulates a basic smart microgrid system using MATLAB/Simulink. It focuses on integrating a solar PV array with a DC-DC boost converter and a DC-AC inverter to supply an AC load. The system is built using Simscape and Specialized Power Systems blocks.


# 🧩 System Overview

*Architecture:*

Solar PV---Boost Converter---DC Bus---Inverter(Universal Bridge)---AC load 


-PV Module: Converts solar irradiance into DC power.
-Boost Converter: Increases PV voltage to match inverter input.
-Universal Bridge Inverter: Converts DC to AC using IGBT switches.
-AC Load: Represents residential or industrial demand.
-PWM Control: Controls switching for boost and inverter stages.
-Measurement Blocks: Monitor voltages and currents across stages.

---

# 🛠️ Technologies Used

-MATLAB/Simulink
-Simscape Electrical (Specialized Power Systems)
-Control & PWM signal generation
-Scopes for waveform visualization

---

# 📊 What You Can Observe

-PV output voltage/current
-Boosted DC bus voltage
-Inverter AC output waveform
-Power quality at the load

---

# 📂 Files Included

-SOLARPV.slx – Main Simulink model
-Screenshot.png – Block diagram for quick reference
-README.md – Project documentation

---

# 📌 Notes

-This simulation does not include MPPT, battery storage, or grid synchronization — it's designed to highlight the core conversion chain from solar to AC load.

-Future versions may include dynamic load switching, SOC-based control, or grid-tied operations.

---

# 🧠 Author

DERICK AMEYAW FREMPONG  
Electrical/Electronic Engineer | Power Systems Enthusiast  
Ghana Ports and Harbours Authority

---

# 📫 Contact
Email: derickameyawfrempong@gmail.com

For questions or collaboration, feel free to reach out via GitHub or email.
