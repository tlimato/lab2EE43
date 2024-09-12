# lab2EE43
### Circuit Transfer Function Documentation

This document outlines the transfer function and associated resistances for specific nodes in a circuit. The data provided details the relationship between the input voltage source (VS) and the output voltages at three different points: \( V(U1\_3) \), \( V(U1\_6) \), and \( V(U2\_6) \). The transfer function is the ratio of the output voltage at a specific point to the input voltage (VS).

---

#### 1. **Transfer Function for \( V(U1\_3) \) / VS**
   - **Transfer Function**: 0.1647 (164.7 mV/V)
     - This indicates that for every 1V applied at the input (VS), the voltage at node \( U1\_3 \) is 164.7 mV.
   - **Input Resistance**: 1.257 kΩ
     - The resistance at the input, which influences how much current flows into the circuit from the input source.
   - **Output Resistance**: 173 Ω
     - The resistance at the output node \( U1\_3 \), which affects how the circuit delivers the output signal to the next stage or load.

---

#### 2. **Transfer Function for \( V(U1\_6) \) / VS**
   - **Transfer Function**: 0.002364 (2.364 mV/V)
     - This indicates that for every 1V applied at the input (VS), the voltage at node \( U1\_6 \) is 2.364 mV.
   - **Input Resistance**: 1.257 kΩ
     - The resistance at the input remains the same as measured for \( V(U1\_3) \), indicating consistent input characteristics.
   - **Output Resistance**: 33.10 Ω
     - The output resistance at node \( U1\_6 \), influencing how the circuit interacts with subsequent components or stages.

---

#### 3. **Transfer Function for \( V(U2\_6) \) / VS**
   - **Transfer Function**: 0.00002622 (26.22 µV/V)
     - This indicates that for every 1V applied at the input (VS), the voltage at node \( U2\_6 \) is 26.22 µV.
   - **Input Resistance**: 1.257 kΩ
     - As with the previous nodes, the input resistance remains consistent at 1.257 kΩ.
   - **Output Resistance**: 54.55 Ω
     - The output resistance at node \( U2\_6 \), which affects how the circuit provides the signal to external components or the next stage.

---

### Summary of Transfer Functions:

| Node        | Transfer Function (V/V) | Input Resistance (Ω) | Output Resistance (Ω) |
|-------------|-------------------------|-----------------------|-----------------------|
| \( U1\_3 \) | 0.1647 (164.7 mV/V)      | 1.257 kΩ              | 173 Ω                 |
| \( U1\_6 \) | 0.002364 (2.364 mV/V)    | 1.257 kΩ              | 33.10 Ω               |
| \( U2\_6 \) | 0.00002622 (26.22 µV/V)  | 1.257 kΩ              | 54.55 Ω               |

---

### Notes:
- **Transfer Function**: Defines how much of the input voltage signal (VS) is transferred to the output node. A higher value indicates more of the input signal is passed through to the output.
- **Input Resistance**: Refers to the resistance that the input voltage sees when applied to the circuit. It remains consistent across the measured points in this circuit.
- **Output Resistance**: This resistance determines how much the output signal is influenced by external loads or components connected to the output node.

This documentation provides an overview of the voltage transfer characteristics and resistances within the circuit for reference and further analysis.
