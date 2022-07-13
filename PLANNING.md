# The plan
I want to build an OS from scratch.
I want to build a CPU and GPU from scratch that can run it.

# What I have so far
### Single-Cycle MIPS-like CPU (FPGA)

- A MIPS-subset CPU (32 bit little-endian)
- Could extend to the full ISA if necesssary
- 100MHz
- Messy datapath, likely difficult to pipeline
- Not huge, lots of room left over on FPGA (TODO get LEs)

### VGA Core

- 640x480 @60Hz
- 25 MHz pixel clock
- 12-bit color (?)
- Very simple: Easy to interface via MMIO
