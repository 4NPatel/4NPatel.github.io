---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
.pubtitle {
    background: #BD666D;
    color: white;
    font-size: 12px;
    padding: 1px 5px;
    border-radius: 15px;
    float: left;
    font-weight: bold;
    margin-right: 6px;
}
.font-bold {
    font-weight: bold;
}
</style>

<span class='anchor' id='about-me'></span>

I am an undergraduate student in Electronics and Communication Engineering at [Nirma University](https://nirmauni.ac.in/), Ahmedabad, India, with a minor in Computer Science and Engineering. My academic interests lie at the intersection of computer architecture, memory systems, parallel computing, and hardware–software co-design.

I am currently a Research Intern working with [Prof. Shounak Chakraborty](https://www.durham.ac.uk/staff/shounak-chakraborty/#overview) at Durham University, United Kingdom, on computer architecture and GPU memory systems. My research explores **STT-RAM-based GPU translation lookaside buffer (TLB) architectures**, focusing on address translation, memory hierarchy design, and the performance implications of asymmetric memory access latencies. I use architectural simulation frameworks, including gem5 and MGPUSim, to investigate design trade-offs in GPU memory systems.

My broader interests include GPU architecture, memory hierarchies, emerging memory technologies, AI accelerators, and efficient hardware architectures for machine learning workloads. I am particularly interested in understanding how architectural innovations and hardware–software co-design can improve performance, energy efficiency, and scalability in modern computing systems.

Alongside my research, I have hands-on experience in RTL design, ASIC physical design, FPGA-based acceleration, and digital VLSI design. My project work includes a weight-stationary systolic array for matrix multiplication, SRAM circuit design, RTL-to-GDSII implementation, and digital design verification.

I am interested in research opportunities in **computer architecture, GPU systems, memory systems, and AI accelerator design**, particularly projects that connect architectural research with practical hardware implementation.

[CV](../publication/cv.pdf) | [GitHub](https://github.com/4NPatel/) | [LinkedIn](https://www.linkedin.com/in/neel-patel-a626301b8/)

---
<span class="anchor" id="research-interests"></span>
# Research Interests

- Computer Architecture and GPU Microarchitecture
- GPU Memory Systems and Address Translation
- Cache Hierarchies, TLBs, and Emerging Memory Technologies
- Parallel Computing and Architectural Simulation
- AI Accelerators and Transformer Inference Architectures
- Hardware–Software Co-design
- RTL Design, Digital VLSI, and ASIC Implementation

<span class="anchor" id="research-experience"></span>
# Research Experience

### Research Intern — Computer Architecture and GPU Memory Systems
*June 2026 – Present*

Research collaboration with *[Prof. Shounak Chakraborty](https://www.durham.ac.uk/staff/shounak-chakraborty/#overview)*, Durham University, United Kingdom.

- Investigating STT-RAM-based GPU L2 TLB architectures for address translation and memory management in modern GPUs.
- Evaluating the architectural implications of asymmetric STT-RAM read and write latencies on TLB design and performance.
- Using gem5 and MGPUSim to study GPU memory-system behavior and evaluate architectural design trade-offs.
- Exploring TLB hierarchy organization and interconnect design to understand their effects on address-translation performance.

### Research Work — Transformer Architectures and KV-Cache Optimization
*Research collaboration*

- Studied Transformer architectures, attention mechanisms, and large language model inference, emphasizing memory and data-movement bottlenecks.
- Explored KV-cache organization and memory-efficient inference techniques, with an interest in architectural approaches to improving inference efficiency.

### MeitY / Chips to Startup (C2S) Research Project
*Secure and Energy-Efficient Mixed-Domain Compute-in-Memory-Based AI Accelerator Chip for Edge Applications*

- Contributing to SRAM circuit design and memory-system research for energy-efficient compute-in-memory-based AI acceleration.
- Studying memory design considerations for hardware-efficient edge AI workloads.

<span class="anchor" id="selected-projects"></span>
# Selected Projects

### 16 × 16 Weight-Stationary Systolic Array for Matrix Multiplication
- Designed a 256-processing-element systolic array using Verilog for matrix multiplication, with a weight-stationary dataflow.
- Developed and simulated the design using Xilinx Vivado, targeting the ZCU104 FPGA platform.
- Evaluated cycle-level behavior and performance at a 300 MHz target clock frequency.

### Operating System Simulator
- Developed a modular C++ simulator implementing process management, CPU scheduling, virtual memory, two-level paging, memory protection, and mutex-based synchronization.
- Implemented Round Robin, Priority, and Shortest Job First scheduling algorithms.

### C++ Expression Compiler
- Developed a modular C++ expression compiler supporting lexical analysis, parsing, expression evaluation, and intermediate representation (IR) generation.
- Implemented abstract syntax tree (AST)-based expression processing and symbol-table management to translate parsed expressions into an intermediate representation.

### 4×4 SRAM Array Design and Layout
- Designed and simulated a 4×4 SRAM array in Cadence Virtuoso, including bitcells, precharge circuits, and associated peripheral circuitry.
- Completed layout design, DRC/LVS verification, parasitic extraction, and post-layout simulations to evaluate read/write behavior.

<span class="anchor" id="publications"></span>
# Publications

<ul>
<li>
<div class="pubtitle">SpliTech 2025</div>
<a href="https://doi.org/10.23919/SpliTech65624.2025.11091648">DL-based Framework for Detecting Malicious Proof-of-Stake Blocks in Gaming Transactions.</a>
<a href="https://ieeexplore.ieee.org/author/886133734934900">J. Gor</a>, <a href="https://ieeexplore.ieee.org/author/622723929181208">K. Dave</a>, <span class="font-bold"><a href="https://ieeexplore.ieee.org/author/37085777412">N. Patel</a></span>, <a href="https://ieeexplore.ieee.org/author/821423846401004">K. Gohil</a>, <a href="https://ieeexplore.ieee.org/author/37272679300">R. Gupta</a>, <a href="https://ieeexplore.ieee.org/author/37077575700">S. Tanwar</a>, <a href="https://ieeexplore.ieee.org/author/37400150700">K. Saleem</a>, and <a href="https://ieeexplore.ieee.org/author/37396654000">J. J. P. C. Rodrigues</a>.
2025 10th International Conference on Smart and Sustainable Technologies (SpliTech), Bol and Split, Croatia, 2025, pp. 1–6. doi: <a href="https://doi.org/10.23919/SpliTech65624.2025.11091648">10.23919/SpliTech65624.2025.11091648</a>.
</li>
<br>
<li>
<div class="pubtitle">R10-HTC 2024</div>
<a href="https://doi.org/10.1109/R10-HTC59322.2024.10778860">SeeD: AI-based Secure Data Exchange Framework for Connected Electric Vehicles.</a>
<a href="https://ieeexplore.ieee.org/author/622723929181208">K. Dave</a>, <a href="https://ieeexplore.ieee.org/author/886133734934900">J. Gor</a>, <span class="font-bold"><a href="https://ieeexplore.ieee.org/author/37085777412">N. Patel</a></span>, <a href="https://ieeexplore.ieee.org/author/37272679300">R. Gupta</a>, and <a href="https://ieeexplore.ieee.org/author/37077575700">S. Tanwar</a>.
2024 IEEE 12th Region 10 Humanitarian Technology Conference (R10-HTC), Kuala Lumpur, Malaysia, 2024, pp. 1–6. doi: <a href="https://doi.org/10.1109/R10-HTC59322.2024.10778860">10.1109/R10-HTC59322.2024.10778860</a>.
</li>
</ul>


<span class="anchor" id="honors-and-awards"></span>
# Honors and Awards

- **Certificate of Excellence** — Top 1% of the department; Department Rank 2.
- **Academic Distinction** — Second-highest academic standing in Electronics and Communication Engineering across Semesters I–VI.
- **Academic Performance** — CGPA: 9.40/10.

<span class="anchor" id="education"></span>
# Education

- **August 2023 – May 2027 (Expected)**  
  **B.Tech. in Electronics and Communication Engineering**, with a minor in Computer Science and Engineering  
  Nirma University, Institute of Technology, Ahmedabad, India  
  CGPA: 9.40/10 | Department Rank: 2

# Industry Experience

### Hardware Intern — eInfochips / Arrow Electronics
*May 2026 – June 2026*

- Worked on RTL-to-GDSII implementation using a 90 nm ASIC design flow.
- Gained practical experience with digital implementation tools and ASIC design methodology.

### Design for Test (DFT) Intern — MeitY / C2S
*May 2025 – June 2025*

- Worked with memory BIST, logic BIST, and design verification workflows using industry-standard DFT tools.
- Performed fault-oriented simulation and explored design-for-test methodologies for digital integrated circuits.

<span class="anchor" id="technical-skills"></span>
# Technical Skills

- **Programming:** C, C++, Python, MATLAB, Shell Scripting, Assembly
- **Computer Architecture:** GPU Memory Systems, CPU Architecture, Cache Hierarchies, TLBs, Parallel Computing, Architectural Simulation
- **AI Hardware:** Systolic Arrays, Transformer Architectures, Attention Mechanisms, KV-Cache
- **RTL and Digital Design:** Verilog, SystemVerilog, RTL Design, CDC Analysis, RTL Linting
- **Architecture and Simulation Tools:** gem5, MGPUSim
- **ASIC and VLSI Tools:** Cadence Virtuoso, Genus, Innovus; Synopsys VCS and Verdi; SpyGlass; Tessent; Vivado; Quartus

# Leadership and Activities

- **Technical Head**, IEEE Student Branch, Women in Engineering (WIE) Affinity Group, Nirma University.
- **Technical Executive Member**, ECO-Nirma.
- **Executive Committee Member**, CSI-Nirma.
- **Volunteer**, ATS 2024.

# Certifications

- Cadence Digital Design and Verification Academic Curriculum, v1.0.
- Cadence Basic Static Timing Analysis, v3.0.

<hr>

<!-- Optional visitor counter -->
<!--
<a href="https://info.flagcounter.com/">
<img src="https://s11.flagcounter.com/count2/" alt="Visitor Counter" border="0">
</a>
-->
