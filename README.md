
# AXI4-Lite Design Verification using SystemVerilog

## Overview
This project focuses on verifying the functionality of an AXI4-Lite Slave using SystemVerilog. A testbench is developed to test read and write transactions and check protocol behavior.

## Features
- AXI4-Lite read and write transaction verification
- SystemVerilog testbench
- Constrained-random stimulus generation
- Driver and monitor
- Self-checking scoreboard
- SystemVerilog Assertions (SVA)
- Simulation waveform analysis

## Verification Components
- **Generator:** Generates read and write transactions.
- **Driver:** Drives signals to the DUT.
- **Monitor:** Observes interface signals and transactions.
- **Scoreboard:** Compares actual and expected results.
- **Assertions:** Checks AXI4-Lite protocol behavior.

## AXI4-Lite Channels
- Write Address (AW)
- Write Data (W)
- Write Response (B)
- Read Address (AR)
- Read Data (R)

## Tools Used
- SystemVerilog
- QuestaSim / ModelSim
- GTKWave
- Git and GitHub

## Learning Outcomes
- Understanding AXI4-Lite protocol handshaking
- Developing a modular verification environment
- Using assertions for protocol checking
- Verifying read and write operations through simulation

## Author
Anirudh Poojary
