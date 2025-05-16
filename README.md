# Single-Transistor Amplifier Design 🔊

Welcome to the Single-Transistor Amplifier project! This project focuses on designing, simulating, and building a transistor-based amplifier that maintains good linearity and low signal attenuation. The amplifier must deliver a ±0.5V input signal to a 100Ω load, using only **one transistor** and no op-amps.

---

## Project Objective

Design an amplifier that:
- Accepts an input of **±0.5V** through a **100Ω source resistance**.
- Delivers the signal to a **100Ω load**.
- Ensures **less than 10% attenuation**.
- Achieves **good linearity** across the full input range.

---

## Constraints

- Must use **only one transistor** (MOSFET or BJT).
- **No op-amps** are allowed.
- Powered only by **available DC supplies** from the Digilent module.
- Signal must be demonstrated with different **waveforms and amplitudes** up to 0.5V.
- Series 100Ω resistor must be included at the input.

---

## Technologies & Tools Used

- **LTspice** or equivalent: For circuit simulation and gain verification.
- **Analog Discovery 3 (AD3)**: Function generator and oscilloscope.
- **Breadboard and discrete components**: For physical implementation.
- **NPN BJT or nMOS transistor**: Selected based on desired gain and biasing requirements.

---

## Project Deliverables

1. **Schematic & Design Explanation**:
   - Selected transistor type (BJT or MOSFET) and justification.
   - Chosen amplifier topology (e.g., **Common Emitter**, **Common Source**).
   - Calculation of biasing, coupling, and gain resistor values.

2. **Simulations**:
   - Model parameters used for the transistor.
   - Simulation types: **Transient**, **DC Sweep**, **Frequency Response**.
   - Measured parameters: **Midband gain**, input/output voltage swing, linearity range.

3. **Physical Circuit Demonstration**:
   - Camera view showing wire mapping between schematic and actual build.
   - Explanation of input and output pathways.

4. **Measurement & Analysis**:
   - Use of AD3 oscilloscope to capture waveform behavior.
   - Measured **midband gain** and comparison with theoretical/simulated values.
   - Linearity validation with a **0.5V input amplitude**.

---

## Key Outcomes

- Demonstrated working amplifier with less than 10% signal attenuation.
- Achieved consistent midband gain across simulation and physical circuit.
- Maintained linear behavior at full input swing.
- Verified proper transistor operation across input signal variations.

---

## Project Files

- `Project 3.asc`: LTspice schematic file.
- [`Watch Video Report`](https://www.youtube.com/watch?v=5SPJJU-ys-s&ab_channel=AaronGhosh): Full walk-through including design explanation, calculations, analysis, simulation, build, and measurement.
