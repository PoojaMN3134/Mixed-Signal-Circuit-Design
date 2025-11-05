# Mixed-Signal-Circuit-Design
Design and Stability Analysis of a Two-Stage CMOS Operational Amplifier
# Project Overview

A two-stage CMOS operational amplifier (op-amp) is a widely used analog circuit designed to achieve high voltage gain, large output swing, and good drive capability. It consists of two main stages:

Differential amplifier (first stage): Provides high input impedance, initial voltage gain, and common-mode noise rejection.

Common-source amplifier (second stage): Boosts the voltage gain and provides the necessary output swing for driving loads.

To ensure stability, a frequency compensation capacitor (Miller capacitor) is connected between the output of the second stage and the input of the second stage (or first-stage output node). This creates a dominant pole and increases the phase margin, thereby preventing oscillations and ensuring a smooth transient response.

# Circuit
<img width="376" height="134" alt="image" src="https://github.com/user-attachments/assets/2acc0e10-9e68-40a5-bac8-c06e6ac9c9ba" />


<img width="675" height="462" alt="Screenshot 2025-11-05 131848" src="https://github.com/user-attachments/assets/e885b1e9-4701-46a5-b169-172c4dc20dec" />

![1](https://github.com/user-attachments/assets/70a5d008-940e-4bd9-88b0-96855e295bae)

# Schematic Circuit
<img width="1920" height="1080" alt="Screenshot from 2025-11-05 12-49-35 1" src="https://github.com/user-attachments/assets/b1f04710-1ff4-474f-9cfd-960421e1996a" />

# Symbol
<img width="1920" height="1080" alt="Screenshot from 2025-11-05 12-49-56 1" src="https://github.com/user-attachments/assets/54eacc8c-63b3-485c-8bc7-64dc51047282" />

# Test Circuit
<img width="1920" height="1080" alt="Screenshot from 2025-11-05 12-49-26 1" src="https://github.com/user-attachments/assets/ada899c0-6b72-45ff-838a-53d27b00a13e" />




