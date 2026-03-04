
# 3-Bit Magnitude Comparator Design

This project covers the full-custom CMOS design and simulation of a 3-bit magnitude comparator. The system compares two 3-bit binary numbers (A and B) and determines if A > B, A < B, or A = B.

## Design Methodology

* **Hierarchical Approach**: Built the system by combining smaller logic modules like NAND, NOR, and NOT gates.
* **Transistor Sizing**: Optimized the width-to-length (W/L) ratios of the transistors to ensure the circuit switches reliably.
* **Technology**: Designed using the TSMC 0.35μm CMOS process library.

## Performance Results

* **Logic Verification**: Confirmed that the output matches the truth table for all possible 3-bit input combinations.
* **Switching Stability**: Used DC analysis to set a stable switching point at 2.5V, providing strong noise margins.
* **Timing Analysis**: Measured the propagation delay to ensure high-speed operation under transient conditions:
    * **Rising Edge**: 904 ps
    * **Falling Edge**: 1.42 ns

## Repository Contents

* **Schematic_Modules**: High-resolution S-Edit schematics for the 3-bit system and individual logic modules.
* **DC-Analysis**: Voltage Transfer Characteristic (VTC) curves and noise margin optimizations.
* **Netlists**: The raw T-Spice code used for the transistor-level simulations.
* **Validation**: Functional verification tests proving the comparison logic works.
