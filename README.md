# Mohamed Tayeb

Final-year engineering student at **Grenoble INP - Phelma**, specializing in
Microelectronics and Telecommunications, currently on exchange at **KTH
Royal Institute of Technology**. Expected graduation: 2027.

I am interested in embedded systems, hardware validation and digital design.
My industrial experience includes embedded C firmware, Python test automation
and electronic measurement. My academic work covers FPGA/ASIC implementation
and radar signal processing.

**Seeking a 20-26-week final-year internship in 2027. Start date flexible.**

## Selected engineering projects

| Project | Implementation and verification |
|---|---|
| [Embedded validation bench](https://github.com/momo347t/embedded-validation-bench) | Portable C acquisition firmware, bounded COBS/CRC serial protocol, Python capture and fault-injection tests. Native firmware validation and an RP2040 hardware target; physical measurements remain to be recorded. |
| [FPGA ITCH market-data decoder](https://github.com/momo347t/market-data-fpga) | SystemVerilog decoder for eight ITCH 5.0 payload types, ready/valid flow control, bounded event FIFO and malformed-frame diagnostics. Independent Python reference, directed/random simulation and reproducible synthesis. |
| [Streaming Q1.15 FIR](https://github.com/momo347t/streaming-fir-q15) | 32-tap fixed-point filter with a time-shared MAC, signed saturation and backpressure. Bit-exact and cycle-exact Python scoreboard, operator/resource checks and implementation reports. |

[![Decoder checks](https://github.com/momo347t/market-data-fpga/actions/workflows/ci.yml/badge.svg)](https://github.com/momo347t/market-data-fpga/actions/workflows/ci.yml)
[![FIR checks](https://github.com/momo347t/streaming-fir-q15/actions/workflows/ci.yml/badge.svg)](https://github.com/momo347t/streaming-fir-q15/actions/workflows/ci.yml)
[![Firmware and host checks](https://github.com/momo347t/embedded-validation-bench/actions/workflows/ci.yml/badge.svg)](https://github.com/momo347t/embedded-validation-bench/actions/workflows/ci.yml)

Each project includes a runnable demo, an interface contract and reproducible
checks. The FPGA projects have been simulated and synthesized, with reports
tied to their RTL versions. The acquisition bench runs the actual C firmware
core against deterministic virtual peripherals and supplies a Pico target.
Physical board measurements are not yet recorded for these portfolio
implementations; their READMEs distinguish those limits from native results.

## Current focus

- SystemVerilog RTL, ready/valid protocols and fixed-point arithmetic.
- Embedded C, binary interfaces and Python acquisition/test automation.
- Reference models, electronic measurement and hardware debugging.
- ASIC/FPGA hardware and digital electronics coursework at KTH.

[LinkedIn](https://www.linkedin.com/in/mohamed-tayeb347/)
