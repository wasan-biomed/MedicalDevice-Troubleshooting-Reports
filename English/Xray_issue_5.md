# Incident Report – X-ray Room System (Siemens Multix Fusion)

- Incident Date: 2024-05-22  
- Device: X-ray Room System – Siemens Multix Fusion  
- Serial Number: XR-881102-L  
- Department: Radiology – Room 2

---

## Problem Description

The device failed to emit any radiation when the exposure button was pressed,  
despite all on-screen settings being correct and no error messages displayed.

---

## Initial Inspection

- Patient and DR panel alignment was verified → correct  
- kV and mAs settings were checked → correct  
- Multiple imaging protocols (chest, extremities) were tested → same result

---

## Root Cause Analysis

Internal inspection revealed that the **interlock switch** on the X-ray room door was **not properly connected**,  
which prevented radiation generation due to safety interlock conditions.  
The disconnection was likely caused by a **strong jolt during room cleaning**.

---

## Corrective Action Taken

- Accessed the internal interlock switch and inspected the wiring  
- Reconnected and secured the loose cable  
- Performed a phantom test exposure → device functioned normally  
- Logged the incident in the service record

---

## Preventive Action

- Cleaning staff were instructed not to touch or move wall-mounted components or safety switches  
- Installed a protective plastic cover over sensitive connector points  
- Added "Interlock check" to the daily pre-operation checklist

---

## Responsible Engineer

- Name: Wasan Qusay Hasan  
- Supervisor Approval: [Signature]  
- Next Scheduled Maintenance: 2024-07-22
