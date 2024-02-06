# Interview Prepration

Collects all the resources I need for interview prep, related to Computer Architecture, RTL and FPGA design, RISC-V and some embedded systems stuff. This is all the stuff KSP talked about and other things I have collected over a while through Linkedin questions, personal interview experiences and whatever I have learned through the years so far, with much more to cover in the future.

Todo:

## Add questions/topics related to

- Embedded Systems Topics
- Chisel and UCB BAR related stuff
- Chipyard - RocketChip, BOOM
- FPGA specific stuff
- RISC-V Assembly programming
- Platform bringup/bootup for RISC-V
- RISC-V Tools - spike, pk, qemu, compilers
- Clang/LLVM and gcc for riscv
- Keep upto date with Tenstorrent, Rivos, SiFive etc news
- Have a look at BUDA and TTmetal
- Ocelot Vector Unit

## The Topics to Cover

This can be broken down into:

### 1. RTL/FPGA + Digital design questions

- Synchronous/Async reset + uses
- Setup and Hold Time
- Clock Slew and Skew
- Static Timing Analysis
- Metastability and Hazards
- Basic Structure of a Latch and Flip-Flop
- Latch vs Flip-Flop
- SRAM Cell (6T, and more) working and diagrams
- Race around condition and Master-Slave FFs
- Clock Divider Logic: /2 and /3 with equal and unequal duty cycles
- Impulse Detector Logic
- Greycodes
- Counters with reset
- Encoder and Decoder Logic
- Greycounter, Ring counter
- FIFO Usage and Depth Calculation
- Mux and Demux Logic
- Mux and Demux trees
- Clock Gateing
- Procedural and Continious Assignment
- Initial and Always Block
- Binary and One-Hot Encoding
- Meeley and Moore State Machines
- Clock Domain Crossing

More complicated/higher level topics:

- Multipliers/Dividers
- Fast Algorithms for Mul/Div
- Floating Point Arithmetic: FP32, BFP16 etc.
- AMBA (AHB, AXI) interconnect architectures
- DDR Controllers
- Multiply and Accumulate MACC units
- Tensor Matrix Multiply

All of these in terms of Verilog and Logic design and circuit design

Not really part of of digital design, but can still be asked this shit

- CMOS Inverter Diagram and Characterstics
- Why NAND over NOR for designs
- CMOS Inverter working basics
- CMOS Stick Diagram for VLSI circuits

### 2. Computer Architecure questions

- Single Cycle, Multicycle and Pipelined
- Pipelining
- Basic Blocks of a CPU
- 5-Stage RISC Machine Architecture
- Harvard Architecture and Von Nuwmann Architecute
- Pipeline Hazards - RAW, WAR, WAW, RAR
- Caches and Cache Structure - Direct, k-Way Associative etc
- Data Flow Machines/Architectures
- Data Dependencies and True Data Dependency
- Amdahl's Law
- ASIC and FPGA Design Flow
- Data Flow and Control flow in processor pipeline
- Power Performance Area
- Addressing Modes (more of an embedded systems topic)

A bit more involved and advanced Topice

- Out-of-Order Execution
- Register Renaming and Reorder Buffer
- Tomasalo's Algorithm
- OoO Execution and In-Order Commit
- Precise Interrupts and Exceptions
- Multi-Scalar/Multi-Issue Processors
- Execution Units
- Branch Prediction and Fetch Engine
- Commit Engine
- SIMD and Vector Processing
- Memory Heirarchy and Caches
- SoC Architecure and Advantages
- Network-on-Chip basics
- Decoupled Architectures - FPU, Vector Unit, Load/Store Unit
- Communication protocols for decoupled units - AMBA, Tilelink, VCIX, UCIe etc.
- Virtual Memory, MMU, Linux and Memory Pages

### 3. RISC-V Specific

- march and mABI
- RISC philosophy
- Brainiacs vs Speed Demons
- Load/Stores in RISC-V (auipc and lw/sw) 20-bit vs 32-bit address
- Atomic Extension and AMO
- How interrupts are handled - PLIC, AIA, CLINT
- Traps/Exception Handeling
- Privilaged Architecuture - Machine Mode, Supervisor Mode, User Mode
- Physical Memory Protection
- Opcodes and Instruction types - Reg Type, Imm Type, Ld/St type, Jump and Branch Instructions
- ISA Extensions - Multiply, Floating Single and Double Precision(FD), Atomic, Compressed
- Load Reserved, Store Conditional
- RISC-V Vector Extension
- Important CSRs

### Interesting questions I've been asked in interviews

- What prevents us (designer) from making the clock speed arbitirarily high?
- What is the difference between async and sync reset and where do we use each of them?
