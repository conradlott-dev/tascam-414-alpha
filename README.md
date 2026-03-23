# Tascam 414-Inspired Saturation Plugin (Python Prototype)

## Why I Have Chosen This Project
I hope to bridge practical audio engineering experience with digital signal processing.
Instead of generic saturation processing, i want to analyse and model the behaviour of real hardware and translate these characteristics into digital systems.

## Overview
This project explores the development of a cassette-style saturation effect using Python and digital signal processing (DSP) principles.

It will:
-Process audio files
-Apply controllable saturation
-Demonstrate aliasing and oversampling
-Form the basis for hardware-referenced DSP modelling

## Current Status
Alpha prototype

## Current Capabilities
- Real-time style DSP pipeline (offline processing)
- Adjustable input gain and saturation drive
- RMS-based autogain for fair comparison
- Tone shaping via simple filtering
- Oversampling prototype to reduce aliasing
- Hardware comparison workflow (in progress)

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
