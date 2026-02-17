# 6T-SRAM-CELL
## 6T SRAM Cell with Sense Amplifier (180nm Technology)
📌 Project Overview

This project presents the design and simulation of a 6-Transistor (6T) SRAM cell integrated with a Sense Amplifier implemented using 180nm CMOS technology. The objective of this project is to analyze the read, write, and hold operations of the SRAM cell and evaluate its performance in terms of stability, power, and speed.

The design is implemented and simulated at transistor level to understand practical memory circuit behavior used in modern VLSI systems.

## 🧠 What is 6T SRAM?

A standard 6T SRAM cell consists of:

Two cross-coupled CMOS inverters (4 transistors)

Two access transistors controlled by the word line

The cell stores 1-bit data and maintains it as long as power is supplied.

Key Operations:

Write Operation

Read Operation

Hold Operation

## 🔎 Sense Amplifier

A Sense Amplifier is used to detect small voltage differences between bit lines during the read operation.

Since SRAM bit-lines develop very small voltage differences, the sense amplifier:

Amplifies the small differential voltage

Improves read speed

Reduces read delay

Enhances reliability

This project uses a differential sense amplifier for fast and accurate read detection.

## ⚙️ Technology Used

Technology Node: 180nm CMOS

Supply Voltage: 1.8V

Transistor Type: NMOS & PMOS

Design Level: Transistor-level schematic

## 🛠 Tools Used
LTSpice

CMOS 180nm PDK

Transient and DC analysis simulations


## 📊 Simulation Results

The following results were analyzed:

Write '1' and Write '0' waveform

Read operation waveform

Bit-line differential voltage

Sense amplifier output waveform

Static Noise Margin (SNM) (if calculated)

Power consumption (if calculated)

## Observations:

Successful read and write operations achieved.

Sense amplifier correctly amplified small bit-line voltage difference.

Stable hold condition observed.

Proper functionality at 1.8V supply.

## 📐 Circuit Description
6T SRAM Cell

2 Pull-up PMOS

2 Pull-down NMOS

2 Access NMOS transistors

Word Line (WL) controls access transistors.
Bit Lines (BL & BL̅) are used for read/write operations.

Sense Amplifier

Differential input from BL & BL̅

Cross-coupled latch structure

Converts small voltage difference to full logic swing output

## 🚀 Applications

Cache Memory

Embedded Memory in Microcontrollers

High-speed On-chip Memory

VLSI Systems

## 📚 Learning Outcomes

Through this project, I gained:

Deep understanding of SRAM cell working

Hands-on experience with transistor sizing

Knowledge of read stability and write margin

Understanding of sense amplifier operation

Experience in 180nm CMOS technology simulation

## 🔮 Future Improvements

Layout design and DRC/LVS verification

Monte Carlo analysis

Power optimization

SRAM array implementation

Comparison with 8T SRAM cell
