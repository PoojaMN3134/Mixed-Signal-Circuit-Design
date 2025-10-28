# Mixed-Signal-Circuit-Design
Design and Stability Analysis of a Two-Stage CMOS Operational Amplifier
# Project Overview

A two-stage CMOS operational amplifier (op-amp) is a widely used analog circuit designed to achieve high voltage gain, large output swing, and good drive capability. It consists of two main stages:

Differential amplifier (first stage): Provides high input impedance, initial voltage gain, and common-mode noise rejection.

Common-source amplifier (second stage): Boosts the voltage gain and provides the necessary output swing for driving loads.

To ensure stability, a frequency compensation capacitor (Miller capacitor) is connected between the output of the second stage and the input of the second stage (or first-stage output node). This creates a dominant pole and increases the phase margin, thereby preventing oscillations and ensuring a smooth transient response.
