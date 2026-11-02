# VoltScope

**Mixed-signal data acquisition and hardware validation system**  
*Status: Work in progress*

VoltScope is a planned electrical engineering project focused on mixed-signal design, embedded firmware, and measurement validation. The goal is to design a small multi-channel data acquisition system that conditions analog signals, samples them with an STM32 microcontroller, and streams the data to a Python interface for analysis.

## Planned features

- Design a 4-channel mixed-signal PCB in KiCad.
- Build analog front-end circuitry with signal conditioning, RC filtering, and input protection.
- Develop STM32 firmware using ADC and DMA for real-time signal sampling.
- Stream captured data to a host computer over UART.
- Visualize waveforms, spectra, and noise behavior in Python.
- Validate circuit behavior using SPICE simulations.

## Proposed stack

KiCad · STM32 · C · ADC/DMA · UART · Python · SPICE

## Engineering focus

VoltScope is intended to demonstrate experience in:

- PCB design and schematic capture
- Analog and mixed-signal circuits
- Embedded systems and microcontroller firmware
- Signal acquisition and measurement systems
- Simulation and hardware validation

## Roadmap

- [ ] Design schematic and select components
- [ ] Create PCB layout in KiCad
- [ ] Simulate analog front-end using SPICE
- [ ] Develop STM32 firmware for multi-channel sampling
- [ ] Stream captured data to Python analysis tools
- [ ] Build a simple dashboard for waveform and FFT visualization

> This repository currently documents a project in development. No fabricated board, measured data, or verified performance results are claimed yet.
