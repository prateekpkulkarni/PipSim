# PipSim

**PipSim** is a Python-based RISC-V pipeline simulator that models a 5-stage instruction pipeline (IF, ID, EX, MEM, WB) with support for hazard detection, simple branch prediction, and cycle-by-cycle visualization. It serves as an educational tool for computer architecture learners and supports basic RISC-V instructions.

> 📄 Full documentation and report available in [`documentation.pdf`](./documentation.pdf)

---

## ✨ Features

- 📌 Instruction parsing and classification (R/I/S/B/U/J types)
- 🔄 Pipeline execution with stage-wise simulation
- ⛔ Data hazard detection and stalling
- 🔁 1-bit branch predictor
- 💾 Simulated register file and memory
- 📊 Visualized pipeline timeline using `matplotlib`

---

## 📦 Supported Instructions

- **Arithmetic**: `add`, `sub`, `addi`
- **Logic**: `and`, `or`, `xor`, `andi`, `ori`, `xori`
- **Shift**: `sll`, `srl`, `sra`, `slli`, `srli`, `srai`
- **Control Flow**: `beq`, `bne`, `blt`, `bge`, `jal`, `jalr`
- **Upper Immediate**: `lui`, `auipc`
- **(Planned)**: Load/Store (`lw`, `sw`, `lb`, `sb`, `lbu`, `sbu`)

---

## 🖥️ Requirements

- Python 3.8+
- Jupyter Notebook

Install dependencies:

```bash
pip install -r requirements.txt
