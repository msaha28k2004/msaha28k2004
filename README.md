<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=26&pause=1200&color=00E6FF&center=true&vCenter=true&width=900&lines=Digital+Design+Engineer;RTL+Design+%7C+FPGA+%7C+ASIC;Timing-Clean+Production-Ready+RTL" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/RTL-Verilog%20%7C%20SystemVerilog-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Verification-SVA%20%7C%20Self_Checking-purple?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Focus-Timing%20%7C%20CDC%20%7C%20Quality-green?style=for-the-badge"/>
</p>

---

## 👋 About

**Digital Design Engineer** focused on **robust RTL, verification, and implementation** for **FPGA and ASIC flows**.

I design **clean, synthesizable, timing-aware hardware** with verification planned from day one.  
This repository is a **curated portfolio** — not demos — showing how I build **production-ready digital systems**.

---

## 🧠 Strengths

- RTL & microarchitecture (pipelines, FSMs, datapaths)
- Assertion-driven verification (SVA)
- CDC-safe design (async FIFOs, synchronizers)
- Timing-aware coding & constraints (SDC/XDC)
- FPGA prototyping & ASIC-friendly RTL

---

## 🚀 Highlight Projects

**Pipelined RISC CPU** – 5-stage pipeline with hazards & forwarding  
**UART Controller** – Parameterized, verified TX/RX FSMs  
**Async FIFO** – CDC-correct, Gray pointers, safe sync  

> Focus: correctness, timing, and clarity — not complexity.

---

## 🧪 Verification Mindset

```systemverilog
assert property (@(posedge clk)
  disable iff (!rst_n)
  req |-> ##1 gnt
);
