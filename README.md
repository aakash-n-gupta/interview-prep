# Interview Prepration
Collects all the resources I need for interview prep, related to Computer Architecture, RTL and FPGA design, RISC-V and some embedded systems stuff. This is all the stuff KSP talked about and other things I have collected over a while through Linkedin questions, personal interview experiences and whatever I have learned through the years so far, with much more to cover in the future.

## The Topics to Cover
This can be broken down into: 
### 1. RTL/FPGA + Digital design questions 
- Synchronous/Async reset + uses
- Setup and Hold Time
- clock Slew and Skew
- Static Timing Analysis
- Metastability and Hazards
- Clock Divider Logic -- /2 and /3 with equal and unequal work cycles
- Impulse Detector Logic
- FIFO Usage and Depth Calculation
- Mux and Demux Logic
- Mux and Demux trees
- Clock Gateing
- Procedural and Continious Assignment
- Initial and Always Block
- Binary and One-Hot Encoding
- Meeley and Moore State Machines
- Clock Domain Crossing
All of these in terms of Verilog and Logic Design states

Not really part of of digital design, but can still be asked this shit
- CMOS Inverter Diagram and Characterstics
- Why NAND over NOR for designs
- CMOS Inverter working basics
- CMOS Stick Diagram for basic logic circuits


### 2. Computer Architecure questions
- Pipelining
- 5-Stage RISC Machine Architecture
- Caches and Cache Structure - Direct, Associative etc
- Harvard Architecture and Von Nuwmann Architecute
- Data Flow Machines
- Pipeline Hazards - RAW, 
- Data Dependencies and True Data Dependency
- ASIC and FPGA Design Flow
- Data Flow and Control flow in processor pipeline
- Basic Blocks of a CPU
- Single Cycle, Multicycle and Pipelined
- Power Performance Area
- Addressign Modes

A bit more involved and advanced Topice
- Multiple Issue, OoO Execution and In-Order Commit
- Tomasalo's Algorithn
- Multi-Scalar Processors
- Precise Interrupts and Exceptions
- SIMD and Vector Processing
- Memory Heirarchy and Caches
- Virtual Memory, MMU, Linux and Memory Pages
- SoC Architecure and Advantages
- Network-on-Chip basics and what it does
- Decoupled Architectures - FPU, Vector Unit, Load/Store Unit
- Branch Prediction and Fetch Engine
- Register Renaming and Reorder Buffer
- Commit Engine
- Execution Units
### 3. RISC-V specifics for Microarchitecture and Embedded Programming
- march and mABI
- RISC phylsofy
- Brainiacs vs Speed Demons
- How Load/Stores are handled in RISC-V
- How interrupts are handled - PLIC, AIA
- Traps/Exceptions
- Priv architecuture - Machine Mode, Supervisor Mode, User Mode
- Physical Memory Protection
- ISA Extensions - Floating Single and Double Precision(FD), Atomic, Compressed
- Atomic Load/Stores
- Load Reserved, Store Conditional
- RISC-V Vector Extension
- Important CSRs and their use

