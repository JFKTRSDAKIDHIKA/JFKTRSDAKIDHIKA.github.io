---
permalink: /
title: "Shu-ao Jia | 贾树傲"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am **Shu-ao Jia (贾树傲)**, an undergraduate student in **Electronic and Communication Engineering** at the **Beijing University of Posts and Telecommunications (BUPT)**. My research interests lie at the intersection of **computer architecture**, **VLSI and circuit design**, and **design automation**.

I am interested in building efficient computing systems from architectural exploration to hardware implementation and optimization. My current research focuses on processing-in-memory architectures for large language model inference and differentiable scheduling for DNN accelerators.

## Education

**B.Eng. in Electronic and Communication Engineering**<br>
Beijing University of Posts and Telecommunications (BUPT), Beijing, China<br>
September 2023 – July 2027 (expected)

- Weighted average: **91.1 / 100** (top **4.6%**, as of January 2026)
- CET-4: 664 · CET-6: 566

## Research

### Tri-Stack-PIM: heterogeneous multi-die 3D-integrated processing-in-memory

I am the first author of **Tri-Stack-PIM: A Heterogeneous Multi-Die 3D-Integrated Processing-in-Memory Architecture for Efficient LLM Inference**, accepted at **IEEE/ACM ICCAD 2026**. The work proposes a heterogeneous multi-die 3D-integrated PIM architecture that disaggregates LLM inference across a DRAM die, a mature-node buffer die for interface, control, and nonlinear engines, and an advanced-node base die for dense SIMD MAC arrays.

I designed **UBAR**, a hardware out-of-order micro-scheduler with a multi-term priority function that recovers up to 90% of the cycles forfeited by in-order policies. Joint architecture–dataflow co-exploration with multi-objective Bayesian optimization reduced energy-delay product by 33–66% and achieved 4.95× / 2.57× / 1.68× geometric-mean speedup over GPU / AttAcc / H2-LLM across MHA, GQA, and MQA workloads.

### FADiff: fusion-aware differentiable optimization for DNN scheduling

I am the first author of **FADiff: Fusion-Aware Differentiable Optimization for DNN Scheduling on Tensor Accelerators**, accepted at **ASP-DAC 2026**. FADiff uses a fusion-aware differentiable optimization framework to efficiently search for high-quality latency and energy schedules in DNN accelerator design spaces.

## Selected Projects

### RISC-V SoC design
**August 2024 – May 2025**

Developed a full-stack RISC-V SoC project from microarchitecture through OS boot. I independently designed a pipelined RV32E core in Chisel, implemented instruction cache, CSR, file, and exception/interrupt handling, and built a differential-testing infrastructure against NEMU using Verilator. The design was synthesized and statically timed with Yosys and iSTA, then validated by booting RT-Thread on the target platform.

### Blind parameter estimation and coherent demodulation of over-the-air QPSK signals
**June 2026**

Designed and implemented a coherent QPSK receiver on RTL-SDR / Simulink. The receiver estimates signal parameters under noise—including roll-off factor, center frequency, occupied bandwidth, symbol rate, and pulse-shaping type—and performs matched filtering, Barker-code synchronization, a Costas-loop carrier recovery loop, Gardner timing recovery, and convolutional-code decoding.

## Experience

**Intern, Cross-Arch & Arch Performance Evaluation and Benchmarking**<br>
*SPEC 2026, Beijing Open Source Chip Research Institute* · July 2026 – present

Working under Dr. Fang Li on benchmarking and characterizing processor performance across ISAs and microarchitectures using the SPEC CPU 2006 suite. The work compares architectural bottlenecks and quantifies microarchitectural efficiency differences across RISC-V, ARM, and x86 platforms.

## Honors

- First Prize, Beijing College Students Integrated Circuit Design Competition (Analog IC Track), 2026
- University-level Scholarship, BUPT, 2024 and 2025
- Third Prize, National English Competition for College Students (NECCS), 2024

## Technical Skills

- **Languages:** C/C++, Python, SystemVerilog, Verilog, Chisel, Bash
- **Hardware & EDA:** VCS, Virtuoso, Cadence, Vivado, ICC2, Design Compiler, PrimeTime, Chipyard, Timeloop, Accelergy
- **Development:** Linux, Git, Vim, tmux

## Contact

For research collaboration or other inquiries, email [pkjia@ss.bupt.edu.cn](mailto:pkjia@ss.bupt.edu.cn) or call +86 151 7542 7075.
