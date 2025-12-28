# 🚀 RISC-V ISA & Toolchain: Architectural Deep-Dive

An intensive technical repository documenting the end-to-end flow of the **RISC-V Instruction Set Architecture (ISA)**. This project tracks the progression from high-level C-based application development to low-level RTL verification.

---

## 🛠️ Tech Stack & Ecosystem

| Category | Tools & Specifications |
| :--- | :--- |
| **ISA** | RISC-V (RV64IMAFDC) |
| **Compiler** | RISC-V GNU Embedded Toolchain (`riscv64-unknown-elf-gcc`) |
| **Simulation** | Icarus Verilog (`iverilog`) |
| **Waveforms** | GTKWave |
| **Environment** | Ubuntu/Linux |

---

## 📑 Technical Learning Path

### 🔹 Software to Hardware Bridge
* **C to Assembly Pipeline:** Compiled C programs into RISC-V object code and performed deep-dive analysis using `objdump`.
* **ABI & Function Calls:** Implemented assembly functions using standard RISC-V calling conventions (register mapping for `a0-a7` and `s0-s11`).

### 🔹 Microarchitecture & RTL
* **Logic Synthesis:** Analyzed the digital logic gate requirements for executing specific instructions within the core.
* **Functional Verification:** Ran simulations of compiled binaries on a RISC-V core and verified timing via GTKWave.
* **STA & Physical Design:** Exposure to Static Timing Analysis and the RTL-to-GDSII flow for silicon realization.

---

## 📈 Key Engineering Highlights
* **Performance Benchmarking:** Analyzed instruction counts and clock cycles for high-level algorithms.
* **Register Mastery:** Demonstrated precise control over argument passing and stack management in assembly.
* **RTL-to-GDSII:** Gained foundational knowledge of physical design constraints and frequency limits in modern CPU cores.

---

## 📂 Repository Structure
```text
├── Task 1-6/       # Lab assignments and task solutions
├── .gitignore      # Filters simulation artifacts (.vcd, .out)
├── LICENSE         # MIT Open Source License
└── README.md       # Project documentation
