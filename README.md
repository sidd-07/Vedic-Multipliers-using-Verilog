# Vedic-Multipliers-using-Verilog

## 🔥 Overview
This repository contains a complete hierarchical implementation of **Vedic multipliers** based on the **Urdhva–Tiryagbhyam Sutra**, supporting:
- 2×2  
- 4×4  
- 8×8  
- 16×16  
- 32×32  
- 64×64  

These multipliers are recursively built and fully synthesizable for FPGA-based DSP, image processing, and AI accelerator applications. The design is optimized for **reconfigurable-precision MAC units**, where dynamic bit-width selection greatly improves power and area efficiency.

---

## 🚀 Key Features
- ✔ Full hierarchy: 2×2 → 4×4 → 8×8 → 16×16 → 32×32 → 64×64  
- ✔ Based on Urdhva–Tiryagbhyam Sutra  
- ✔ FPGA-friendly RTL, no vendor primitives  
- ✔ Modular & reusable architecture  
- ✔ Suitable for DSP, CNNs, filters, and neural accelerators  
- ✔ Ideal foundation for reconfigurable MAC architectures  

---
---

## 🧩 Vedic Multiplier Hierarchy

### 🔹 2×2 Vedic Multiplier  
Base block using Urdhva–Tiryagbhyam for parallel partial-product calculation.

### 🔹 4×4 Vedic Multiplier  
Constructed using four 2×2 multipliers and efficient adders.

### 🔹 8×8 Vedic Multiplier  
Constructed using four 4×4 Vedic modules.

### 🔹 16×16 Vedic Multiplier  
Constructed using four 8×8 Vedic modules.

### 🔹 32×32 Vedic Multiplier  
Constructed using four 16×16 Vedic modules.

### 🔹 64×64 Vedic Multiplier  
Top-level architecture using four 32×32 blocks.  
Forms the computational core of reconfigurable MAC architectures.

---

## 🧠 Why Vedic Multipliers?

Traditional multipliers include:
- Array multipliers  
- Booth multipliers  
- Wallace-tree multipliers  
- Dadda multipliers  
- Shift-and-add multipliers  

These architectures involve trade-offs in area, delay, and power—often leading to long critical paths, high wiring complexity, and large switching activity.

### ⭐ Advantages of Vedic Multipliers
- Parallel generation of partial products  
- Very low propagation delay  
- Highly scalable hierarchical structure  
- Reduced area and hardware complexity  
- Ideal for multi-bit reconfigurable systems  

---

## 🧪 Testbench
A generic testbench (`tb_vedic_multiplier.v`) is included for:
- Functional verification  
- Randomized input testing  
- Output validation with reference multiplication  

Works with Vivado, ModelSim, Questa, and Verilator.

---

## ⚙️ FPGA Compatibility
This design is fully synthesizable on:
- Xilinx Spartan-7 / Artix-7 / Kintex Ultrascale  
- Intel Cyclone / Arria  
- Lattice ECP5 / iCE40  
- Any RTL-compatible FPGA  

---

## 📄 Recommended IEEE References
Use the following IEEE papers for your project/thesis:

1. High-Speed Urdhva–Tiryagbhyam Vedic Multiplier Architecture – IEEE  
2. FPGA Implementation of Vedic Mathematics Based Multiplier – IEEE  
3. Low-Power Vedic Multiplier for DSP Algorithms – IEEE  
4. Reconfigurable Precision Vedic MAC Architecture – IEEE  
5. Approximate Vedic Multipliers for Edge AI – IEEE  

---

## 🙋‍♂️ Author
Developed by **Siddartha**  
Research focus: *FPGA-based reconfigurable arithmetic and Vedic multiplier design.*

---

## 🟢 Future Enhancements
- Pipelined Vedic multiplier versions  
- DSP-accelerated leaf multipliers  
- AXI Stream compatible MAC design  
- Low-power clock gating  
- Approximate Vedic multiplier integration  

---

### 🎉 Thank you for visiting the repository!

