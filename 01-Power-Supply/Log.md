# Project Log: Dragon Power Supply (Prototype 1)

**Location:** Tonalá, Jalisco, Mexico

### **July 16, 2025**

#### Summary of Achievements:

Today marked a significant success in the construction of the lab bench power supply prototype. The primary goal was to create a stable, regulated DC output from the core AC transformer, and this was fully achieved.

- **Component Sourcing:** Successfully identified and sourced all necessary components for a fixed 5V regulated output from existing parts, including a UA7805C regulator, a "104" (0.1µF) ceramic capacitor, and a 10µF electrolytic capacitor.
- **Circuit Prototyping:** The complete power circuit was successfully assembled on a breadboard. This included:

  - A full-wave bridge rectifier using 1N4007 diodes.
  - A primary smoothing capacitor to create an unregulated DC bus (~16.8V).
  - The UA7805C regulator circuit with its required input and output filter capacitors.

- **Successful Test & Validation:** The circuit was powered on and performed exactly as designed.

  - **Output Voltage:** The output was measured at 4.8V, which is well within the standard tolerance for a 5V regulated supply.
  - **Load Test:** Successfully powered a 5V DC brushless fan, confirming the circuit can deliver stable power under load.
  - **Indicator:** A power-on indicator LED was successfully integrated into the output.

#### Next Steps:

The project is on schedule. The next phases are:

- **Thursday:** Solder the verified breadboard circuit onto a permanent perfboard.
- **Friday:** Finalize the cardboard enclosure and integrate the circuit, adding external binding posts for easy access to the 5V and Ground rails.
- **Saturday:** Compile project documentation, including photos, the final schematic, and video clips for the weekly social media update.

### **July 14, 2025**

- **Task:** Built the bridge rectifier and main filter capacitor stage on the breadboard.
- **Problem:** None. The output was a clean, albeit high, DC voltage as expected.
- **Solution:** N/A. Milestone achieved.

### **July 12, 2025**

- **Task:** Watched the DroneBot Workshop video on linear power supplies. Sketched out the initial schematic for the multi-output design.
- **Problem:** Unsure about the correct heat sink size for the LM317 regulator under full load.
- **Solution:** Found a datasheet with thermal resistance calculations. Will work through the math in a future session.

### **July 11, 2025**

- **Task:** Began organizing components for the build. Laid out the main parts on the workbench.
- **Problem:** Realized I'm missing my 24V transformers and solder.
- **Solution:** Will start by prototyping the regulator circuits on a breadboard using a temporary power source. Will order new solder tomorrow.
