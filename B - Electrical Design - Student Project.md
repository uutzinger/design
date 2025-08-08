🎓 **Student Project: Low-Power ECG Acquisition Module**

**Project Overview:**  
Students design an **electrical subsystem** for a portable biomedical device — a low-power ECG acquisition and transmission module.  
The goal is to practice **reading, understanding, and creating electrical designs** including schematics, PCB layouts, and signal conditioning circuits.

---

#### **Learning Objectives**
- Interpret and produce **circuit diagrams** for biomedical sensors.
- Select and integrate **passive and active components**.
- Design **analog front ends** for biosignal acquisition.
- Apply **filtering and amplification** to physiological signals.
- Implement **low-power design techniques** for battery-operated devices.

---

#### **Core Design Tasks**
##### 📐 Circuit Design
- Create a **schematic** including:
  - ECG electrodes and lead-off detection.
  - Instrumentation amplifier for signal acquisition.
  - High- and low-pass filtering to remove noise.
  - ADC interface to a microcontroller.

##### 🖥 PCB Layout
- Use PCB design software (e.g., KiCad, Altium, Eagle).
- Apply **trace routing**, **ground plane**, and **isolation techniques** for low-noise operation.
- Ensure proper **connector placement** for electrodes and communication modules.

##### 🔌 Power Management
- Select a low-power microcontroller.
- Design a battery power supply with overcurrent protection.
- Incorporate sleep modes for energy saving.

##### 📊 Testing
- Simulate circuit performance in SPICE.
- Measure signal quality from test waveforms or ECG simulators.
- Verify against **design requirements** for noise, gain, and power consumption.

---

#### **Skills Practiced**
| Domain                | Skills Practiced |
|-----------------------|------------------|
| Circuit Design        | Schematic creation, component selection |
| PCB Design            | Layout, EMI/EMC considerations |
| Signal Processing     | Filtering, amplification |
| Power Electronics     | Battery systems, voltage regulation |
| Testing & Debugging   | Oscilloscope use, signal integrity analysis |

---

#### **Optional Enhancements**
- Add wireless transmission (Bluetooth Low Energy) to send data to a smartphone.
- Include onboard memory for offline data logging.
- Implement multi-lead ECG acquisition.

---

#### **Deliverables**
- Schematic and PCB design files.
- Bill of Materials (BOM) with specifications.
- SPICE simulation results.
- Prototype board and measured signal data.
- Verification report comparing requirements vs results.

---

#### **Safety and Feasibility Notes**
- All testing should use **simulated signals** or approved ECG simulators — no direct patient testing without ethical approval.
- Maintain electrical isolation per **IEC 60601-1** patient safety standards.
