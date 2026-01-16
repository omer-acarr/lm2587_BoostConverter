# LM2587 DC-DC Boost Converter Design

This repository contains the complete design files for a high-efficiency **DC-DC Boost Converter** based on the **Texas Instruments LM2587** Simple Switcher® flyback regulator. The project focuses on robust power delivery, efficient thermal management, and an optimized PCB layout.

---

## 🛠 Technical Specifications

The LM2587 integrated circuit provides all active functions for step-up (boost), flyback, and forward converter switching regulators.

* **Input Voltage Range:** 4V to 40V
* **Output Voltage:** Adjustable (Up to 60V via feedback resistor network)
* **Switch Current:** 5.0 A (Internal NPN Switch)
* **Switching Frequency:** 100 kHz (Internal Oscillator)
* **Protection Features:** Thermal shutdown and current limiting
* **Topology:** Boost (Step-up)

---

## 🚀 Design Highlights & Engineering Considerations

* **Power Integrity:** Optimized copper trace widths for high-current paths to minimize voltage drops and parasitic inductance.
* **Thermal Management:** Implementation of dedicated copper pours and thermal vias under the LM2587 to ensure stable operation under load.
* **EMI/EMC Optimization:** The high-current loop (Input Cap -> Inductor -> Diode -> Output Cap) has been kept as compact as possible to reduce electromagnetic interference.
* **Signal Integrity:** Feedback traces are routed away from the switching node (inductor and switch pin) to prevent noise injection into the control loop.

---

## 📁 Project Structure

* **/Project Outputs:** Manufacturing files including Gerbers and NC Drill files.
* **/Schematics:** Detailed circuit diagrams designed in Altium Designer.
* **/PCB Layout:** 2-layer optimized PCB design with dedicated ground planes.
* **/BOM:** Bill of Materials with manufacturer part numbers and footprints.

---

## 💻 Tools Used

* **ECAD Software:** Altium Designer
* **Simulation:** TI WEBENCH / LTSpice
* **Documentation:** Markdown



