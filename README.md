# Tascam 414-Inspired Saturation Plugin (Python Prototype)

## Overview
This project explores the development of a cassette-style saturation effect using Python and digital signal processing (DSP) principles.

## Current Status
Alpha prototype

## In Progress
- Hardware reference comparison workflow (Tascam 414 mkII)

## Features
- Nonlinear saturation using tanh
- Harmonic analysis via FFT
- RMS-based autogain
- Dry/wet mix control
- Tone filtering
- Aliasing demonstration
- Basic oversampling implementation

## Technologies
- Python
- NumPy
- SciPy
- Matplotlib

## Purpose
Early alpha build exploring DSP relating to saturation and emulation of classic audio hardware such as the Tascam Portastudio.

## How to run
1. Clone repository
2. Install dependencies
3. Open the notebook

## Outcomes
- Understanding nonlinear distortion and harmonic generation
- Managing aliasing in digital systems
- Implementing oversampling techniques
- Structuring DSP workflows in Python

## Next Steps
- Process real WAV files
- Explore asymmetry and tape-style emulation
- Refactor DSP code into Python functions
- Port the prototype into plugin framework
