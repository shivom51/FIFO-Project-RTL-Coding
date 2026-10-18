# FIFO-Project-RTL-Coding
I designed an 8-entry synchronous FIFO using Verilog/SystemVerilog. Each entry stores 8 bits of data. The design uses a write pointer, a read pointer and an occupancy counter to track stored data. Full and empty flags prevent writes when the FIFO is full and reads when it is empty. I developed a self-checking testbench to check data ordering.
