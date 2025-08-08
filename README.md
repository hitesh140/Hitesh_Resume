Project Highlights

1. High-Speed GPIO Interface Design — Sasken Silicon Technologies

During my internship at Sasken Silicon Technologies, I designed a high-speed GPIO interface operating at 125MHz. The project required developing both receiver and transmitter paths between a 1.8V GPIO and a 0.7V core, always staying within strict 1.8V device limits for safe operation. To make the design robust and versatile, I used a 2x architecture that allows support for 3.3V GPIO while ensuring device protection.

The receiver path was designed with a Schmitt Trigger for noise immunity, followed by a high-to-low level shifter and buffer chain, ensuring accurate signal conversion. The transmitter included a low-to-high level shifter, pre-driver, and driver stages for efficient, high-speed output. I also integrated Fail-Safe Circuits into both 1.8V and 3.3V paths to safeguard devices during fault scenarios or voltage mismatches.

To validate the reliability and performance of the design, I performed comprehensive AC/DC verification (VIH, VIL, VOH, VOL, IOH, IOL, rise/fall times, delay, and duty cycle) across all process, voltage, and temperature (PVT) corners. This experience significantly improved my expertise in digital/analog interface design, circuit protection, and rigorous verification methodologies.

2. Single Cycle MIPS Datapath — Computer Architecture Project

As part of my coursework, I implemented a single-cycle Micro-MIPS processor datapath in Verilog. I built key components such as the register file, ALU, and memory blocks, integrating and simulating custom Verilog modules for instruction execution—all adhering to a single-cycle architecture. This project strengthened my understanding of digital logic, processor architecture, and hands-on hardware design and verification practices.
