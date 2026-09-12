---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

## Education

**Beijing University of Posts and Telecommunications (BUPT)**, Beijing, China<br>
**B.Eng. in Electronic and Communication Engineering**, September 2023 – July 2027 (expected)

- Weighted average: 91.1 / 100 (top 4.6%, as of January 19)
- CET-4: 664 · CET-6: 566

## Research Interests

Computer architecture · Circuits and VLSI design · Design automation

## Publications

1. **Shu-ao Jia**, Zichao Ling, Chen Bai, Kang Zhao, Jianwang Zhai. *Tri-Stack-PIM: A Heterogeneous Multi-Die 3D-Integrated Processing-in-Memory Architecture for Efficient LLM Inference.* **IEEE/ACM ICCAD**, San Jose, November 2026. First author. Accepted at ICCAD 2026.
2. Shu-ao Jia, Zichao Ling, Chen Bai, Bei Yu, Kang Zhao, Jianwang Zhai. *FADiff: Fusion-Aware Differentiable Optimization for DNN Scheduling on Tensor Accelerators.* **IEEE/ACM ASP-DAC**, Tokyo, January 2027. Sole first author. Accepted at ASP-DAC 2026.

## Research Projects

### Tri-Stack-PIM: A Heterogeneous Multi-Die 3D-Integrated Processing-in-Memory Architecture for Efficient LLM Inference
**November 2025 – present** · Chip architect and sole first author · Accepted at ICCAD 2026

Proposed Tri-Stack-PIM, a heterogeneous multi-die 3D-integrated PIM architecture that disaggregates LLM inference across a DRAM die, a mature-node buffer die hosting interface, control, and nonlinear engines, and an advanced-node base die dedicated exclusively to dense SIMD MAC arrays. This organization simultaneously resolves keep-out-zone fragmentation, compute–interface contention, logic-density limitations, and hot-spot/fold serializations inherent in prior 2-die designs.

Designed **UBAR**, a hardware out-of-order micro-scheduler with a multi-term priority function that recovers up to 90% of cycles forfeited by in-order policies. Conducted joint architecture–dataflow co-exploration via multi-objective Bayesian optimization, reducing energy-delay product by 33–66% and achieving 4.95× / 2.57× / 1.68× geometric-mean speedup over GPU / AttAcc / H2-LLM across MHA, GQA, and MQA workloads.

### FADiff: Fusion-Aware Differentiable Optimization for DNN Scheduling on Tensor Accelerators
**May 2025 – November 2025** · Sole first author · Accepted at ASP-DAC 2026

Designed FADiff, a fusion-aware differentiable optimization framework for efficient DNN scheduling on tensor accelerators. Designed a unified differentiable analytical cost model for estimating the energy and latency of intra-layer mappings and inter-layer fusion strategies. Integrated CP-SAT-based feasible candidate pre-enumeration with augmented-Lagrangian continuous optimization to efficiently search a large coupled design space, demonstrating superior optimization quality and faster convergence over existing methods on energy and latency metrics.

## Engineering Projects

### RISC-V SoC Design
**August 2024 – May 2025**

Developed a full-stack processor development flow from microarchitecture specification through OS boot. Independently designed a pipelined RV32E core in Chisel; implemented instruction cache, CSR file, and exception/interrupt handling; and built a differential-testing infrastructure against NEMU using Verilator. Performed synthesis and static timing analysis with Yosys and iSTA, then integrated the core into an SoC platform validated by booting RT-Thread.

### Blind Parameter Estimation and Coherent Demodulation of Over-the-Air QPSK Signals on RTL-SDR
**June 2026**

Designed and implemented a coherent QPSK receiver on RTL-SDR / Simulink that blindly estimates unknown over-the-air RF signal parameters and demodulates the signal to recover transmitted ASCII messages in real time. Inferred center frequency, occupied bandwidth, symbol rate, and pulse-shaping type from live spectrum measurements, deriving a 300 kHz symbol rate from a 450 kHz main-lobe bandwidth with a raised-cosine roll-off of α = 0.5.

Built the full demodulation chain—AGC, Costas-loop carrier recovery, Gardner timing recovery, matched filtering, Barker-code frame synchronization, and hard-decision decoding—and validated each stage through constellation, eye-diagram, and spectrum observations. Tuned the receiver for RTL-SDR sampling constraints and widened timing/carrier-recovery loop bandwidths to acquire larger oscillator-induced frequency offsets, successfully decoding a higher-difficulty signal.

## Experience

**Intern — Cross-Arch & Arch Performance Evaluation and Benchmarking with SPEC 2026**<br>
*Beijing Open Source Chip Research Institute* · July 2026 – present<br>
*Supervisor: Dr. Fang Li*

Benchmarks and characterizes processor performance across ISAs and microarchitectures using the SPEC CPU 2006 suite. Conducts cross-architecture comparisons among RISC-V (Kunminghu Lake v3), x86 (AMD Zen 5), and ARM (Neoverse N2 / V2 / V3), identifying architectural bottlenecks and quantifying microarchitectural efficiency differentials.

## Honors & Awards

- First Prize, Beijing College Students Integrated Circuit Design Competition (Analog IC Track), 2026
- University-level Scholarship, Beijing University of Posts and Telecommunications, 2025
- University-level Scholarship, Beijing University of Posts and Telecommunications, 2024
- Third Prize, National English Competition for College Students (NECCS), 2024

## Technical Skills

- **Languages:** C/C++, Python, SystemVerilog, Verilog, Chisel, Bash
- **Hardware & EDA tools:** VCS, Virtuoso, Cadence, Vivado, ICC2, Design Compiler, PrimeTime, Chipyard, Timeloop, Accelergy
- **Development environment:** Linux, Git, Vim, tmux
