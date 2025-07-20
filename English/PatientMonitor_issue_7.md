# Incident Report – Patient Monitor (Nihon Kohden Life Scope G9)

- Incident Date: 2024-05-07  
- Device: Patient Monitor – Nihon Kohden Life Scope G9  
- Serial Number: PM-443221-X  
- Department: Intensive Care Unit – Bed 2

---

## Problem Description

The monitor displayed a persistent alert: “SpO₂ probe error”,  
and no oxygen saturation readings appeared,  
despite the probe being correctly attached to the patient’s finger.

---

## Initial Inspection

- The probe was replaced with a new one → same issue  
- The same probe was tested on another device → working normally  
- The device was restarted → issue persisted

---

## Root Cause Analysis

It was found that the **SpO₂ port** was **damaged internally**,  
due to a **bent metal pin**, most likely caused by forcibly pulling the probe cable.

---

## Corrective Action Taken

- The device was opened, and the input board accessed  
- The entire **SpO₂ port** was replaced with a new spare part  
- Connections were soldered and secured carefully  
- The device was tested using a simulator → normal readings restored

---

## Preventive Action

- Installed a **plastic port protector** to prevent future damage  
- Nursing staff were trained to **pull cables straight and gently**

---

## Responsible Engineer

- Name: Wasan Qusay Hasan  
- Supervisor Approval: [Signature]  
- Next Scheduled Maintenance: 2024-06-07
