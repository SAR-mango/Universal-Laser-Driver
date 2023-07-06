# Universal Laser Driver
Solves the problem of having to match batteries, laser drivers, and diodes based on input and output voltage and current requirements.

## Applications
Intended for low-power laser pointers where space is minimal.

Especially well suited for builds utilizing the Leadlight Pen Host, because the PCB is designed to fit in the plastic carrier that normally holds the switch board. The Leadlight Pen Host requires two 10440-sized battery cells, and the Universal Laser Driver allows the user to swap between AAA alkaline and 10440 Li-ion cells without worrying about damaging the driver or not having sufficient voltage to power the diode.

## Specifications
Vin: 2.25–9V

Vout: 1–7V

Iout: 0–200mA

These can very significantly. Lower Vin and/or higher Vout (due to the nonlinear nature of laser diodes) would result in a lower maximum Iout. A lower Iout setting would extend the Vin and Vout ranges.

## Project Updates
**July 2023**: The test board has been shown to reliably produce stable currents between 0 and 200mA using a test load with six standard silicon diodes and one 1Ω resistor in series. Minimal noise was found in the output current waveform, especially below 20MHz. Noise pulses were no more than several nanoseconds long. Therefore, the Universal Laser Driver is unlikely to cause damage or reduced reliability to even the most delicate laser diodes.

The version of the driver meant for the Leadlight Pen Host will be updated to reflect the current schematic for the test board.
