🚀 RISC-V ISA & Toolchain: Architectural Deep-Dive
A comprehensive technical repository documenting the end-to-end flow of the RISC-V Instruction Set Architecture (ISA). This project covers the transition from high-level C programming to hardware implementation, focusing on Application Binary Interface (ABI) and RTL-level verification.

🛠️ Technical Learning Path
The workshop was structured into six critical stages of computer architecture development:
Task 1: C to Assembly Pipeline – Exploring the RISC-V GNU Toolchain (riscv64-unknown-elf-gcc) and analyzing object code via objdump.
Task 2: Integer & Floating Point ISA – Deep-dive into RV64I and RV64F instruction formats and register usage.
Task 3: ABI & Function Calls – Implementing assembly functions that interface with C code using standard RISC-V calling conventions.
Task 4: Logic Synthesis & RTL – Understanding the digital logic gates required to execute specific instructions within a RISC-V core.
Task 5: Timing Analysis & Static Timing (STA) – Evaluating the performance and frequency limits of a custom RISC-V core.
Task 6: Final Verification – Running functional simulations of compiled C programs on the RISC-V core using iverilog and GTKWave.

💻 Tech Stack & Tools
ISA: RISC-V (RV64IMAFDC).
Compiler: RISC-V GNU Embedded Toolchain.
Simulation: Icarus Verilog (iverilog).
Waveform Analysis: GTKWave.
Operating System: Ubuntu/Linux environment.

📊 Key Highlights
Performance Benchmarking: Analyzed instruction counts and clock cycles for various C-algorithms (e.g., Sum of N numbers).
Register Management: Mastered the use of a0-a7 for arguments and s0-s11 for saved registers in assembly.
RTL-to-GDSII Flow: Exposure to the physical design constraints involved in bringing a RISC-V core to silicon.

📂 Repository Structure
├── Task 1-6/      # Daily lab assignments and task solution
├── .gitignore     # Filters out simulation artifacts (.vcd, .out)
├── LICENSE        # MIT Open Source License
└── README.md      # Technical documentation
