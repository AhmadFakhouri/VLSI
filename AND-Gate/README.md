# CMOS AND Gate Transient Analysis

This project involves the implementation and timing verification of a CMOS AND gate. The focus was on measuring high-speed transient performance and propagation delays.

## Methodology

* **Circuit Implementation**: Developed the multi-stage logic schematic in S-Edit.
* **Transient Simulation**: Ran a time-domain simulation over a 100ns window using T-Spice to verify high-frequency switching.
* **Timing Extraction**: Used W-Edit to accurately measure the rising and falling edges of the output signal.

## Performance Results

* **Rising Edge Delay**: Measured at 318.9 ps.
* **Falling Edge Delay**: Measured at 325.3 ps.
* **Speed Verification**: The sub-nanosecond delay results confirm the design's suitability for high-speed digital systems.

## Repository Contents

* **Schematic_Modules**: Full-custom AND gate schematic.
* **Transient-Analysis**: Waveform screenshots showing the sub-nanosecond timing.
* **Netlists**: Simulation netlists for transient verification.
