# Half_Adder_90nm
The Half Adder is a combinational circuit used to perform the addition of two single-bit binary numbers.
Features
- **Design**: Implementation using fundamental logic gates (AND, XOR).
- **Optimization**: Reduced area and improved delay.
- ## Truth Table
| A | B | Sum | Carry |
|---|---|-----|-------|
| 0 | 0 |  0  |   0   |
| 0 | 1 |  1  |   0   |
| 1 | 0 |  1  |   0   |
| 1 | 1 |  0  |   1   |


**Equation**
- Sum = A^B
- Carry = A.B
- 
  **Tools Used**
- **Cadence Virtuoso** 
- Technology Node: **90nm** 

---

## 📐 Schematic Design

![Half Adder Schematic](https://github.com/nitya-0105/Half_Adder_90nm/blob/main/Half_Adder_Design.jpg)

The schematic includes CMOS implementations of XOR (for SUM) and AND (for CARRY) gates. It is optimized for logic correctness and area efficiency.

---

## ⏱️ Transient Analysis

![Transient Output](./halfadder_waveform.JPG)

- Simulation shows correct SUM and CARRY outputs based on input A and B.
- **Delay**, **rise/fall time**, and **glitch behavior** are observed for performance analysis.
- Results validated against theoretical timing expectations.

---

## ✅ Design Rule Check (DRC)
![DRC check](https://github.com/nitya-0105/Half_Adder_90nm/blob/main/HAlf_Adder_DRC.jpg)
- DRC was performed using the layout editor in Cadence.
- No rule violations were found under 130nm technology constraints.

---

## 🧾 Layout vs Schematic (LVS)
![LVS check](https://github.com/nitya-0105/Half_Adder_90nm/blob/main/Hald_Adder_LVS.jpg)
- LVS confirms that the layout matches the original schematic.
- Pin names and net connectivity verified using extraction.

---


