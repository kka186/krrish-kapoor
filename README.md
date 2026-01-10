# 👋 Hi, I’m Krrish Kapoor

🎓 **Mechatronic Systems Engineering Student**  
📍 Langley, BC | Simon Fraser University  
 Mechanical • Electrical • Computational Systems

I’m a Mechatronics Engineering student with a strong interest in modeling, analyzing, and designing multidisciplinary systems that integrate mechanical structures, electrical circuits, and computational tools. My experience spans structural mechanics, dynamic systems, circuit analysis, and experimental validation using both simulation and real-world measurements.

---

## Technical Skills

**Programming & Computation**
- Python
- MATLAB

**Engineering Tools**
- Multisim
- Granta EduPack
- Arduino

---

## Projects

---

# Mechanical Analysis of a Cessna 172 Aircraft Wing

<details>
  <summary><b>What?</b></summary>
  <br>

  Analyzed the structural integrity of a Cessna 172 wing spar under a conservative loading case (⅓ max takeoff weight) to identify the critical section and assess safety under bending and shear.

  <p align="center">
    <img src="images/wing_model.png" width="85%" />
  </p>
</details>

<details>
  <summary><b>How?</b></summary>
  <br>

  Simplified the wing into an equivalent beam with pinned–strut support. Solved reaction forces using equilibrium and compatibility, then built shear and bending moment distributions. Evaluated stresses at the critical section using Mohr’s Circle and ductile failure criteria.

  <p align="center">
    <img src="images/fbd_front.png" width="48%" />
    <img src="images/fbd_forces.PNG" width="48%" />
  </p>
</details>

<details>
  <summary><b>Result</b></summary>
  <br>

  Identified a safety deficit in the baseline design and used results to justify design improvements (material and/or geometry changes). Final outputs included bending moment and shear force diagrams to highlight the governing region and load path.

  <p align="center">
    <img src="images/bending.png" width="48%" />
    <img src="images/shear.png" width="48%" />
  </p>
</details>

---

# Transient Response of RC and RL Circuits (Experimental Lab)

<details>
  <summary><b>What?</b></summary>
  <br>

  Measured how first-order RC and RL circuits respond to step inputs, focusing on time constants, charging/discharging behavior, and the agreement between theory and real measurements.

  <!-- Add your lab setup photo(s) here once uploaded:
  <p align="center">
    <img src="images/Transient Response of RC Circuits/<your_image>.png" width="85%" />
  </p>
  -->
</details>

<details>
  <summary><b>How?</b></summary>
  <br>

  Collected voltage/current waveforms during step excitation and extracted time constants using standard response landmarks (e.g., 63.2% method). Compared experimental curves to predicted exponential models and documented error sources (instrument limits, component tolerances, and non-ideal behavior).

  <!-- Add your oscilloscope plots / circuit schematic photos here:
  <p align="center">
    <img src="images/Transient Response of RC Circuits/<your_image>.png" width="48%" />
    <img src="images/Transient Response of RC Circuits/<your_image>.png" width="48%" />
  </p>
  -->
</details>

<details>
  <summary><b>Result</b></summary>
  <br>

  Verified first-order model behavior in real hardware and quantified deviations from theory. Reported measured time constants and explained discrepancies through practical non-idealities.

  <!-- Add your final comparison plot(s) here:
  <p align="center">
    <img src="images/Transient Response of RC Circuits/<your_image>.png" width="85%" />
  </p>
  -->
</details>

---

# Transient Response of Multi-Resistor RC Circuits Using Multisim

<details>
  <summary><b>What?</b></summary>
  <br>

  Simulated transient behavior of an RC network with multiple resistors to understand effective resistance/capacitance behavior, time constant changes, and waveform shape under step inputs.

  <p align="center">
    <img src="images/Transient Response of Multi-Resistor RC Circuits Using Multisim/circuit_schematic.png" width="85%" />
  </p>
</details>

<details>
  <summary><b>How?</b></summary>
  <br>

  Built the circuit in Multisim, applied step excitation, and compared simulated outputs against hand calculations using equivalent resistance methods (including Thevenin-style reduction where appropriate).

  <p align="center">
    <img src="images/Transient Response of Multi-Resistor RC Circuits Using Multisim/multisim_circuit.png" width="85%" />
  </p>
</details>

<details>
  <summary><b>Result</b></summary>
  <br>

  Produced transient response plots and extracted an effective time constant from simulation, showing how network structure changes the observed exponential response compared to a single-resistor RC model.

  <p align="center">
    <img src="images/Transient Response of Multi-Resistor RC Circuits Using Multisim/time_constant.png" width="85%" />
  </p>
</details>

---

# Modelling of Mechatronic Systems Using Mechanical–Electrical Analogies

<details>
  <summary><b>What?</b></summary>
  <br>

  Characterized the dynamics of a mass–spring–damper system and modeled the behavior using an equivalent RLC circuit analogy to connect mechanical intuition with electrical response.

  <p align="center">
    <img src="images/Electrical Analogies/oscar.png" width="48%" />
    <img src="images/Electrical Analogies/FBD_MSD.png" width="48%" />
  </p>
</details>

<details>
  <summary><b>How?</b></summary>
  <br>

  Estimated key second-order parameters (natural frequency and damping) from measured response trends, then mapped mechanical parameters to electrical equivalents (R, L, C). Built and tested the analog circuit to compare expected and observed response behavior.

  <p align="center">
    <img src="images/Electrical Analogies/rlc_conversion.png" width="85%" />
  </p>
</details>

<details>
  <summary><b>Result</b></summary>
  <br>

  The electrical analog reproduced the main mechanical trends across frequency, including resonance and phase behavior. Final outputs included frequency response magnitude and phase plots to validate the analogy.

  <p align="center">
    <img src="images/Electrical Analogies/magnitude_freq.png" width="48%" />
    <img src="images/Electrical Analogies/phase_freq.png" width="48%" />
  </p>
</details>

---

# Materials Selection: Aircraft Turbine Fan Blade (Granta EduPack + Eco Audit)

<details>
  <summary><b>What?</b></summary>
  <br>

  Selected an optimal fan blade material by balancing performance, reliability, cost, and environmental impact. The goal was a defensible choice under realistic constraints (temperature capability, stiffness/strength, fatigue and fracture considerations).

  <p align="center">
    <img src="images/Aircraft Turbine Fan Blade/blade_cavity.png" width="48%" />
    <img src="images/Aircraft Turbine Fan Blade/material_table.png" width="48%" />
  </p>
</details>

<details>
  <summary><b>How?</b></summary>
  <br>

  Screened candidates using engineering constraints and compared finalists using material charts, indices, and weighted decision criteria. Used an Eco Audit to compare lifecycle energy/CO₂ drivers across the top options.

  <p align="center">
    <img src="images/Aircraft Turbine Fan Blade/naturalfreq_tensile_stress.png" width="85%" />
  </p>
</details>

<details>
  <summary><b>Result</b></summary>
  <br>

  Identified a best overall candidate and justified it using the combined scoring and environmental comparison. Final outputs summarize the top-ranked material choice and the reasoning behind the selection.

  <p align="center">
    <img src="images/Aircraft Turbine Fan Blade/nickelbased_superalloy.png" width="85%" />
  </p>
</details>



---

## 📫 Contact & Links

- 💼 LinkedIn: *https://www.linkedin.com/in/krrish-kapoor-957b07310/*
- 📧 Email: kka186@sfu.ca

---


