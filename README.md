# UVM-Testbench-for-a-simple-routing-protocol
# UVM Testbench — Simple Router

This repository contains a **UVM testbench** for a simple packet router with **1 input channel, 3 output channels, and an HBUS interface** for CSR configuration.  
The environment was built as part of the **Cadence SystemVerilog Accelerated Verification with UVM** course.  
It includes agents for YAPP input, channel outputs, HBUS, clock/reset, along with a **scoreboard and virtual sequencer**.  
Test sequences configure router registers via HBUS and generate packets to verify correct routing and max-packet handling.  
To run the project, **simulate `src/tb/tb_top.sv`** with your simulator (e.g., `xrun -uvm src/tb/tb_top.sv`).  
