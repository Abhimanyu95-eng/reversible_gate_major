---
Design & Analysis of Arithmetic Circuit using Reversible Logic Gates
---
This project presents the design and simulation of reversible logic–based arithmetic circuits using Toffoli, Peres, and Feynman gates. The arithmetic units designed include a reversible full adder and a reversible multiplier, implemented and analyzed using Cadence Virtuoso with CNTFET device models integrated through Verilog-A.

Reversible logic enables one-to-one mapping between input and output vectors, avoiding information loss and reducing energy dissipation — a fundamental advantage over irreversible CMOS logic as described by Landauer’s principle.
The work focuses on power-efficient computing architectures for next-generation VLSI and nanotechnology platforms. 

---
Methodology:
---

Logical Design of reversible gates

Construction of reversible full adder and multiplier

Transient simulations under 0.9–1.8 V supply voltage

Extraction of performance parameters including Power, Delay, and PDP

Comparative analysis of delay and power across different technologies 

---

Results Summary:
---

Peres gate achieved the lowest transistor count and quantum cost

All reversible circuits exhibited successful logical and transient responses

Power and delay were extracted for 90 nm and 45 nm implementations

Reversible architecture demonstrated strong potential for low-power computing 

---

Challenges Encountered:
---

Minimizing garbage outputs and constant inputs

Designing multiplier with optimized quantum cost

Achieving signal copying without violating reversibility

Power-delay optimization for reversible circuits 

---

Future Improvements:
---

Reversible ALU and reversible DCT blocks

Sequential reversible circuits (flip-flops, registers)

Optimization focused on quantum cost, garbage outputs, and circuit depth

Integration toward quantum and nanotechnology platforms

---
