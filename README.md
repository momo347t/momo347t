# Mohamed Tayeb

Final-year engineering student at **Grenoble INP - Phelma**, specializing in
Microelectronics and Telecommunications, currently on exchange at **KTH
Royal Institute of Technology**. Expected graduation: 2027.

I am interested in FPGA design, digital hardware and the verification of
streaming systems. My background includes embedded C, Python test automation
and academic FPGA/ASIC implementation work.

**Seeking a 20-26-week final-year internship in 2027. Start date flexible.**

## Selected hardware projects

| Project | Implementation and verification |
|---|---|
| [FPGA ITCH market-data decoder](https://github.com/momo347t/market-data-fpga) | SystemVerilog decoder for eight ITCH 5.0 payload types, ready/valid flow control, bounded event FIFO and malformed-frame diagnostics. Independent Python reference, directed/random simulation and reproducible synthesis. |
| [Streaming Q1.15 FIR](https://github.com/momo347t/streaming-fir-q15) | 32-tap fixed-point filter with a time-shared MAC, signed saturation and backpressure. Bit-exact and cycle-exact Python scoreboard, operator/resource checks and implementation reports. |

[![Decoder checks](https://github.com/momo347t/market-data-fpga/actions/workflows/ci.yml/badge.svg)](https://github.com/momo347t/market-data-fpga/actions/workflows/ci.yml)
[![FIR checks](https://github.com/momo347t/streaming-fir-q15/actions/workflows/ci.yml/badge.svg)](https://github.com/momo347t/streaming-fir-q15/actions/workflows/ci.yml)

Each project includes a runnable demo, an interface contract, test commands
and reports tied to the RTL version. The READMEs explain implementation
scope and the limits of the timing experiments. These
portfolio implementations have been simulated and synthesized; they have
not been validated on a physical FPGA board.

## Current focus

- SystemVerilog RTL, ready/valid protocols and fixed-point arithmetic.
- Reference models, reproducible tests and hardware debugging.
- ASIC/FPGA hardware and digital electronics coursework at KTH.

[LinkedIn](https://www.linkedin.com/in/mohamed-tayeb347/)
