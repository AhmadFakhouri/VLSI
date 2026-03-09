# CMOS NOR Gate DC Optimization

This project focuses on the design and DC analysis of a 2-input CMOS NOR gate. The goal was to optimize the transistor sizing to achieve a balanced switching threshold and high noise margins.

## Methodology

* **Schematic Design**: Created the full-custom transistor-level schematic in Tanner S-Edit.
* **DC Sweep Analysis**: Performed a DC sweep in T-Spice to analyze the Voltage Transfer Characteristic (VTC).
* **Transistor Sizing**: Experimented with various width ratios to find the ideal balance between the pull-up and pull-down networks.

## Performance Results

* **Optimal Ratio**: Determined that a width ratio of Wn=20Wp provided the most stable performance.
* **Switching Point**: Successfully stabilized the switching threshold at exactly 2.5V.
* **Noise Margins**: The symmetric VTC ensures high noise immunity for digital logic operations.

## Repository Contents

* **Schematic_Modules**: Transistor-level S-Edit screenshots.
* **DC-Analysis**: VTC curves and DC sweep simulation results.
* **Netlists**: Raw T-Spice netlist files.
