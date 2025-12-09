# Buck Converter Analysis in LTspice

This project demonstrates the simulation and analysis of a **DC-DC Buck converter** using LTspice. The circuit uses realistic components to reflect practical behavior, including:

- **MOSFET:** IRFZ48N  
- **Schottky diode:** MBR735  
- **LC filter with ESR** for smoothing the output  

---

## Circuit Functionality

- **Input:** 15 V DC  
- **Output:** Regulated via a PWM signal  
- **Switching element:** MOSFET controlled by a custom comparator (`MyComparator`) and an internally generated sawtooth waveform  
- **Filtering:** LC filter provides stable DC output with minimal ripple  

---

## Analysis Performed

- **Transient behavior:** Observes switching dynamics, overshoot, ripple, and ESR effects  
- **Frequency response:** Frequency sweep with complex measurements yields magnitude, phase, and gain (Bode-style analysis)  
- **Detailed measurements:** Average voltage, real/imaginary components, and derived gain/phase demonstrate advanced simulation techniques  

---

## Key Takeaways

- Solid understanding of DC-DC switching converter design  
- Ability to simulate and analyze both time-domain and frequency-domain behavior  
- Practical understanding of ESR and MOSFET characteristics  
- Ability to interpret simulation results and connect them to real-world converter performance  

---

This project is ideal for demonstrating skills in **power electronics**, **circuit simulation**, and **control-loop analysis**. It can serve as a discussion point for job interviews or portfolio presentations.
