# Mixed-Signal-Circuit-Design
Design and Stability Analysis of a Two-Stage CMOS Operational Amplifier

# Circuit
<img width="376" height="134" alt="image" src="https://github.com/user-attachments/assets/2acc0e10-9e68-40a5-bac8-c06e6ac9c9ba" />

The two-stage operational amplifier consists of:
1. Differential Input Stage (M1–M4, M5)
Transistors M1 and M2 form an NMOS differential pair that receives the input signals.
M3 and M4 act as a current-mirror load, converting the differential signal to a single-ended output.
M5 provides a constant tail current, ensuring proper biasing and defining the input common-mode range (ICMR).
Function: Converts differential input voltage into an amplified current.

2. Gain Stage (M6)
The output of the first stage drives transistor M6, configured as a common-source amplifier.
This stage provides most of the voltage gain of the op-amp.
Function: Further amplifies the signal to achieve high gain.

3. Output Stage / Load Drive (M7)
Transistor M7 drives the load capacitance (C<sub>L</sub>) and delivers output current.
Function: Drives external load with low output impedance.

4. Frequency Compensation (C<sub>C</sub>)
A compensation capacitor is connected between the first-stage output and second-stage input.
It introduces a dominant pole and improves phase margin and stability.

<img width="675" height="462" alt="Screenshot 2025-11-05 131848" src="https://github.com/user-attachments/assets/e885b1e9-4701-46a5-b169-172c4dc20dec" />

![1](https://github.com/user-attachments/assets/70a5d008-940e-4bd9-88b0-96855e295bae)
![WhatsApp Image 2025-11-05 at 13 40 13_5f62f2f5](https://github.com/user-attachments/assets/030478a9-b923-4fc6-b9ce-a10555852cca)

# Schematic Circuit
<img width="1440" height="784" alt="Screenshot from 2025-12-02 14-13-43" src="https://github.com/user-attachments/assets/b5af3332-77be-4a16-8bd6-973418db3964" />


# Symbol
<img width="1351" height="824" alt="Screenshot from 2025-11-05 12-49-56 1" src="https://github.com/user-attachments/assets/98d7a103-19eb-4282-a4a6-947f41df3fcc" />


# Test Circuit
<img width="1002" height="799" alt="Screenshot from 2025-11-05 12-49-26 1" src="https://github.com/user-attachments/assets/9e6e2162-da58-42c6-b420-f261e3505d77" />

# Transient Analysis Waveform
![trans 1](https://github.com/user-attachments/assets/edecfdee-868c-427f-b2fc-158c6a224552)

# Bode Plot 
![bode 1](https://github.com/user-attachments/assets/45a09456-f805-4e9b-9fbd-d80f2049a76e)

![WhatsApp Image 2025-11-05 at 13 51 21_2895cfaf](https://github.com/user-attachments/assets/aef0003e-e371-47c6-9f31-2d73f8d0d924)

# DC Analysis Waveform
![dc 1](https://github.com/user-attachments/assets/a904839d-bd04-4054-90d6-bad15d82ac0f)

# AC Analysis Waveform
![ac 1](https://github.com/user-attachments/assets/52f3e515-e2d3-47a0-abcd-5fae5cc0efc3)





