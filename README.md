# Whisker-Puff-Device
Whisker stimulation device for in vivo rodent neurobiology experiments. Uses a pneumatic system controlled by an electromagnetic solenoid valve to direct intermittent air puffs onto a rodent’s whisker pad.


# Overview


* Air is intermittently puffed onto a rodent’s whisker pad while cellular & vascular activity in the corresponding barrel cortex is recorded with widefield microscopy
* Designed to address weaknesses in existing whisker stimulation tools by precisely and evenly distributing stimulation over the whisker pad, while reducing stimulus habituation
* Arduino-based system
* Pneumatic system that delivers room air supply through a nozzle towards the rodent’s whisker pad. The air is pulsed (optionally at randomly varying frequencies) to reduce the rodent’s habituation to the stimulus. This change in airflow is switched through an N-channel MOSFET driving a 3-way electromagnetic solenoid valve.

# Circuit Schematic
<img width="1380" height="956" alt="image" src="https://github.com/user-attachments/assets/0de94d24-2faf-4ad9-8cc7-bc52dd2bdb6c" />

# Usage Example*

<img width="605" height="527" alt="image" src="https://github.com/user-attachments/assets/4d9204f7-448a-44e4-a6dd-bc34831242ff" />

# Bill of Materials
| Component | Part | Notes |
|-----------|------|-------|
| Microcontroller | Arduino UNO R3 | USB-powered |
| MOSFET | IRLB8721 | Logic-level N-channel |
| Solenoid valve | 3-way, 6 V | External supply |
| Gate resistor | 270 Ω | Gate to Arduino pin |
| Pneumatic Tubing| 3mm Silicone Tubing | Connect between air supply and solenoid valve input port |
| Switch | SPDT toggle | Override for on/off control |

# User Guide
[Whisker Puff User Guide](https://github.com/marymorris24/Whisker-Puff-Device/blob/main/Copy%20of%20Guide%20To%20Airpuff%20Stimulation.pdf)
