Audio Amplifier Project

This project demonstrates the design, simulation, and hardware implementation of a low-power audio amplifier using the **LM386 IC**. It bridges the gap between weak audio signals from portable devices and the need to drive external speakers.

 Project Overview
*Simulation Tool:LTspice XVII
*Hardware IC:LM386N-4
*Power Supply:9V DC
*Speaker Load:4Ω / 8Ω, 1 Watt

Features
- Amplifies weak audio signals (<1V) to drive low-impedance speakers.
- Compact design suitable for portable electronics.
- Demonstrates clipping behavior when input volume is too high.

 Components
- LM386 IC
- Resistors: 1kΩ × 2
- Capacitors: 100μF × 2, 1000μF × 1, 100nF × 1
- Speaker: 4Ω or 8Ω, 1W
- 9V Battery
- 3.5mm Aux Jack

Results
*Simulation:Verified amplification and observed clipping at high input.
*Hardware:Successfully amplified audio from a phone to a speaker. Clear sound at medium volume, distortion at maximum volume.

Documentation
See the `report_epc.docx` file for detailed circuit diagrams, simulation results, and hardware photos.

License
This project is licensed under the MIT License.
