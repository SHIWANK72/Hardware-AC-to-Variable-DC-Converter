# Hardware-AC-to-Variable-DC-Converter
A hardware project to design and build a regulated AC to variable DC converter using a bridge rectifier and an LM317 voltage regulator.
# Hardware Project: AC to Variable DC Converter

This repository provides documentation for a hardware project that involves the design, assembly, and testing of a power supply circuit. This circuit converts a standard AC input into a variable and regulated DC output, a foundational skill in power electronics.

This is a pure hardware project and does not contain any software code.

## Project Objective
The goal was to create a reliable and stable power supply capable of providing an adjustable DC voltage, suitable for powering various electronic circuits and experiments in a lab environment.

## Circuit Stages & Components
The circuit was designed in four distinct stages:

1. **Transformation**: A step-down transformer (230V to 12V) reduces the high-voltage AC to a safer level.
2. **Rectification**: A full-wave bridge rectifier, using four 1N4007 diodes, converts the AC signal into pulsating DC. 
3.  **Filtration**: A large electrolytic capacitor (1000µF) smooths the pulsating DC, significantly reducing the ripple voltage.
4. **Regulation**: An LM317 variable voltage regulator IC, along with a potentiometer, provides a stable and adjustable DC output (e.g., from 1.25V to 10V). 

## Testing & Validation
The final circuit was tested using a multimeter and an oscilloscope.
- The multimeter confirmed the range of the variable DC output.
- The oscilloscope was used to visualize the waveform at each stage, confirming the effectiveness of the rectification and filtering processes.

## Safety Precautions
Working with AC mains voltage is dangerous. All high-voltage connections were properly insulated, and the circuit was housed in a non-conductive enclosure. A fuse was included on the primary side of the transformer for overcurrent protection.
