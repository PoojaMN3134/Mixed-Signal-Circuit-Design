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
<img width="1920" height="1080" alt="Screenshot from 2025-12-02 15-38-04" src="https://github.com/user-attachments/assets/5d33d78a-8196-4b5a-af24-4f70fa6954d8" />
<img width="2643" height="2728" alt="p1" src="https://github.com/user-attachments/assets/d4170d2f-876a-4438-a0f0-0dade72be9b9" />

# Bode Plot 
<img width="1920" height="1080" alt="Screenshot from 2025-12-02 13-36-05" src="https://github.com/user-attachments/assets/31716eb9-979d-458e-a53d-e693bc3604cc" />

# DC Analysis Waveform
<img width="1920" height="1080" alt="Screenshot from 2025-12-02 14-12-39" src="https://github.com/user-attachments/assets/2388d00f-2c75-4409-98d4-beb8c46ed039" />

# AC Analysis Waveform
<img width="1920" height="1080" alt="Screenshot from 2025-12-02 14-12-13" src="https://github.com/user-attachments/assets/d5b8ecad-4fb2-4117-afc1-b174e15cb130" />

# References:
[1] R. Saidulu, B. P. Chandar, and K. Ravi Kumar, “Design and Simulation of a High Gain Two-Stage Op-Amp Realised in 90 nm CMOS Process,” Journal of Emerging Technologies and Innovative Research (JETIR), vol. 10, no. 5, pp. d47–d54, May 2023.

some papers and books https://drive.google.com/drive/folders/1DwQK6ToqPoA2O_kQzzZrTLDcux04AhlF







