# Incident Report – Ultrasound Device (GE Logiq P5)

- Incident Date: 2024-05-12  
- Device: Ultrasound – GE Logiq P5  
- Serial Number: US-112780-Z  
- Department: Sonography Unit – Second Floor

---

## Problem Description

When the device is powered on, the screen and interface function normally,  
but **no image appears** on the display during probe usage — only a black screen.

---

## Initial Inspection

- Probe was confirmed to be properly connected to the device port  
- Two different probes (Convex and Linear) were tested → same issue  
- Device was restarted multiple times → issue persisted  
- No error messages were displayed on the interface

---

## Root Cause Analysis

Using service tools, it was found that the **Beamformer Board** was not generating any pulses to the probes.  
An internal circuit failure was identified, with **high heat observed** on the board,  
indicating a **fault in the power supply section**, specifically a **damaged capacitor**.

---

## Corrective Action Taken

- Opened the back cover and inspected the Beamformer unit  
- Replaced a **burnt capacitor (100μF / 25V)** on the main board  
- Cleaned the affected area and re-soldered the connections carefully  
- Performed a successful **Self-Test** after reassembly  
- Conducted imaging test using a phantom → normal image display

---

## Preventive Action

- Added Beamformer unit to the **thermal inspection checklist**  
- Recommended improved ventilation and external cooling for long-term operation  
- Submitted a request to stock a **spare Beamformer board** in maintenance inventory

---

## Responsible Engineer

- Name: Wasan Qusay Hasan  
- Supervisor Approval: [Signature]  
- Next Scheduled Maintenance: 2024-06-12
