# DIKWP Cardiac TriageCare RehabOS 2026 V1

A standalone, offline-first reference prototype for cardiac disease triage preparation, treatment coordination, and rehabilitation support.

## Core boundary

This system is **not** a diagnostic device, emergency medical service, prescription system, medical order system, cardiac monitor, or rehabilitation prescription generator. It organizes red flags, evidence, action-level triage, care coordination, rehabilitation domains, and human clinical review.

## Quick start

Open `index.html` in a modern browser. No server, database, model API, account, or network is required.

Optional CLI:

```bash
python tools/run_cardiac_triage.py examples/sample_case_chest_pain.json --out outputs
```

## Main modules

1. Safety boundary and emergency red flags
2. Synthetic case profile
3. C0-C5 action-level triage
4. DIKWP cardiac care closure
5. Care Evidence Ledger
6. Acute chest pain / chest pain center pathway
7. Treatment coordination pathways
8. Cardiac rehabilitation five-prescription model
9. Home monitoring and recurrence warning
10. Medication safety and adherence checklist
11. AI and digital tool guardrails
12. Role and responsibility chain
13. 3-No simulation
14. Cardiac Care Passport

## Prohibited uses

- diagnosis of myocardial infarction, heart failure, atrial fibrillation, aortic dissection, pulmonary embolism, or any other condition
- prescribing, stopping, replacing, or dosing medications
- deciding PCI, thrombolysis, surgery, cardioversion, anticoagulation, or hospitalization
- replacing EMS, emergency department, chest pain center, cardiologist, or cardiac rehabilitation team
- interpreting ECG, troponin, BNP, CT, echo, or wearable data as a final medical decision
- automatic risk ranking of patients, doctors, hospitals, or rehabilitation programs
- covert monitoring, face/voice/emotion-based cardiac assessment, or unauthorized real patient data collection

## Design lineage

The system follows the DIKWP Evidence Ledger → Action Ticket → Human Review → Static Boundary Audit pattern and adapts it to cardiovascular triage, treatment coordination, and rehabilitation.
