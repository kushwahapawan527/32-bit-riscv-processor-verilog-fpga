# 🚀 32-bit RISC-V Processor in Verilog (FPGA Based)

## 📌 Overview
This project presents the design and implementation of a **32-bit RISC-V processor** using Verilog HDL.  
The processor includes core components such as ALU, register file, and control unit, and is simulated using **Icarus Verilog** and **GTKWave**.

---

## 🎯 Features
- 32-bit RISC-V architecture
- ALU (ADD, SUB, AND, OR operations)
- Register File (32 registers)
- Control Unit for instruction decoding
- Modular and scalable design
- Simulation with waveform analysis

---

## 🏗️ Architecture
The processor consists of the following main modules:

- **ALU** – Performs arithmetic and logical operations  
- **Register File** – Stores data in 32 registers  
- **Control Unit** – Decodes instructions and generates control signals  
- **Instruction Memory** – Stores program instructions  
- **Data Memory** – Handles load/store operations  

---

## 🛠️ Tools & Technologies
- Verilog HDL  
- Icarus Verilog (Simulation)  
- GTKWave (Waveform Viewer)  
- FPGA (Target Implementation)

---

## ▶️ How to Run
```bash
# Compile
iverilog src/*.v testbench/*.v

# Run simulation
vvp a.out

# View waveform
gtkwave *.vcd

## 📊 Output
### ALU Output
![ALU](results/alu_output.png)

### CPU Output
![CPU](results/cpu_output.png)
