# Project Log: Dragon Power Supply (Prototype 1)

## **Date: July 18, 2025**

**Location:** Tonalá, Jalisco, Mexico

### Summary of Achievements:

Today was a true test of patience, focused on debugging the perfboard circuit. It was frustrating to see the circuit fail again after soldering, a feeling I remember well from past projects. However, I'm glad to see my tolerance for this kind of frustration has grown. Instead of giving up, I was able to approach it methodically.

- **Problem Identification:** The methodical approach paid off. I confirmed the rectifier stage was faulty by measuring a low DC voltage (~2.6V) across the main capacitor while under load. This proved the capacitor wasn't being recharged.

- **Root Cause Analysis:** I traced the error back to a simple but critical mistake during the initial build: I likely misread the multimeter, measuring AC instead of DC voltage. This distraction led me down the wrong path, but it's a valuable lesson in staying focused.

- **Circuit Rebuild:** I desoldered the faulty bridge and built a new one.

  - Improved Layout: I used a more intuitive "diamond" configuration for the diodes. This layout is much clearer and should help prevent future wiring errors.

  - Successful Stage 1 Test: The new bridge works! Testing without the capacitor gives an ~8V DC reading, which is the expected "average" voltage. This confirms the new assembly is correct.

### Next Steps:

The project is now back on a solid foundation with a validated rectifier stage. The next immediate step is to:

- Solder the main 35V smoothing capacitor to the output of the newly built bridge rectifier.

- Verify that the voltage across the capacitor is a stable ~16-17V DC.

- Proceed with soldering the 5V regulator section onto the perfboard.

## **Date: July 17, 2025**

**Location:** Tonalá, Jalisco, Mexico

### Summary of Achievements:

**Enclosure Fabrication:** Made significant progress on the power supply's case. The cardboard structure was reinforced with internal support ribs, creating a sturdy housing for the switch and AC power cord.

**Permanent Circuit Assembly:** Began the process of creating a permanent, reliable circuit by soldering the components from the breadboard onto a perfboard.

### Problems Encountered:

**Circuit Malfunction:** After soldering, the circuit is not operating correctly. On power-up, the output LED indicator lights up for approximately two seconds and then fades out. This indicates a failure to maintain a stable output voltage under load.

### Next Steps & Troubleshooting Plan:

The immediate priority is to debug the soldered perfboard. The plan is as follows:

- **Systematic Testing:** Adopt a stage-by-stage testing approach.

  - First, test the output of the bridge rectifier alone.

  - Next, add the main smoothing capacitor and verify it holds a stable ~16.8V charge.

  - Finally, re-integrate the 5V regulator section.

- **Soldering Inspection:** Carefully inspect every solder joint for common issues like cold joints (dull or lumpy appearance), solder bridges (accidental connections), or missed connections.

- **Technique Improvement:** Research best practices and tutorials for perfboard soldering to improve wiring techniques for future builds.

## **July 16, 2025**

### Summary of Achievements:

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

### Next Steps:

The project is on schedule. The next phases are:

- **Thursday:** Solder the verified breadboard circuit onto a permanent perfboard.
- **Friday:** Finalize the cardboard enclosure and integrate the circuit, adding external binding posts for easy access to the 5V and Ground rails.
- **Saturday:** Compile project documentation, including photos, the final schematic, and video clips for the weekly social media update.

## **July 14, 2025**

- **Task:** Built the bridge rectifier and main filter capacitor stage on the breadboard.
- **Problem:** None. The output was a clean, albeit high, DC voltage as expected.
- **Solution:** N/A. Milestone achieved.

## **July 12, 2025**

- **Task:** Watched the DroneBot Workshop video on linear power supplies. Sketched out the initial schematic for the multi-output design.
- **Problem:** Unsure about the correct heat sink size for the LM317 regulator under full load.
- **Solution:** Found a datasheet with thermal resistance calculations. Will work through the math in a future session.

## **July 11, 2025**

- **Task:** Began organizing components for the build. Laid out the main parts on the workbench.
- **Problem:** Realized I'm missing my 24V transformers and solder.
- **Solution:** Will start by prototyping the regulator circuits on a breadboard using a temporary power source. Will order new solder tomorrow.
