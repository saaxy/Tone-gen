# VHDL PWM Tone Generator

This project implements a basic PWM (Pulse Width Modulation) generator in VHDL, suitable for use in tone generation (e.g., driving a piezo buzzer or speaker).

## 📁 File Overview

- **PWM_Gen.vhd** — Main VHDL module that generates a PWM signal based on configurable parameters.

## 🔧 Features

- Simple PWM generator
- Frequency and duty cycle control
- Can be used to drive audio signals (e.g., 440 Hz tone)
- Suitable for FPGA boards like Xilinx or Intel/Altera

## 🖥️ Usage

1. Instantiate the `PWM_Gen` module in your top-level VHDL design.
2. Connect it to your board's clock input and desired output pin (e.g., connected to a speaker).
3. Configure the frequency and duty cycle through the input ports.

## 🧪 Example Application

This module can be used to:
- Produce a square wave for audio tones
- Generate PWM signals for motor control or dimming LEDs

## ⚙️ Simulation & Synthesis

- Use a VHDL simulator (e.g., ModelSim, GHDL) to simulate.
- Compatible with most FPGA toolchains (Quartus, Vivado, etc.)

## 📜 License

This project is open-source. Feel free to modify and use in your projects.
