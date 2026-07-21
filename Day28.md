# 🏥 Day 28 – Hospital Admission Readiness Simulator

## 📌 Project Overview

On Day 28 of the ABTalks 60 Days AI Challenge, I built a **Hospital Admission Readiness Simulator** using Claude AI.

This interactive healthcare operations simulator places the user in the role of a **Hospital Admission Coordinator**, responsible for evaluating whether a patient is ready for hospital admission. The simulator combines Prior Authorization workflows, documentation review, insurance verification, clinical risk assessment, and care coordination into a realistic, task-driven experience.

---

# 🎯 Objective

- Simulate the hospital admission readiness process
- Evaluate Prior Authorization workflows
- Assess documentation and insurance readiness
- Track admission risks
- Improve clinical coordination understanding
- Build an interactive healthcare operations simulator

---

# 🚀 Core Features

## 🏥 Hospital Admission Setup

Users configure:

- Provider (Illustrative)
- Attending Physician
- Diagnosis
- Admission Type
- Prior Authorization Status
- Admission Date

The application follows a task-first workflow without displaying a dashboard on startup.

---

## 📋 Admission Readiness Analysis

The simulator evaluates:

- Prior Authorization
- Insurance Verification
- Bed Availability
- Clinical Documentation
- Physician Orders
- Patient Consent

A weighted readiness score is generated before the final admission decision.

---

## 📊 Weighted Readiness Scoring

The readiness score is calculated using:

- Prior Authorization – 25%
- Clinical Documentation – 20%
- Physician Orders – 20%
- Insurance Verification – 15%
- Consent – 10%
- Bed Availability – 10%

Special logic ensures that denied Prior Authorization with ICU admissions cannot achieve high readiness through administrative actions alone.

---

## 🔄 Prior Authorization Workflow

The simulator supports multiple PA outcomes:

- Approved
- Pending
- Denied
- Appeal

Users can complete follow-up actions, upload documentation, contact physicians, and submit appeals to improve admission readiness.

---

## 📈 Timeline Tracking

The admission journey includes:

- PA Review
- Insurance Verification
- Bed Assignment
- Documentation
- Consent
- Patient Arrival
- Registration
- Clinical Assessment
- Admission Complete

---

## 👥 Care Coordination

Interactive coordination cards include:

- Attending Physician
- Case Manager
- Nursing
- Utilization Review
- Discharge Planner

The Utilization Review section highlights concurrent review, denial risk identification, and InterQual/Milliman criteria.

---

## ⚠️ Risk Tracking

The simulator continuously evaluates:

- Documentation Risk
- Insurance Risk
- Bed Risk
- Clinical Risk

Higher clinical risk is automatically assigned for Acute MI, CHF, and ICU admissions.

---

## 📑 Governance Snapshot

When readiness reaches 75% or higher, the simulator displays industry benchmark estimates including:

- Prior Authorization turnaround time
- Inpatient denial rate
- Prior Authorization rework cost

---

## ✅ Final Admission Decision

Based on the readiness score:

- **90% or above:** Admit
- **Below 90%:** Not Ready

The simulator also provides a summary of completed tasks, remaining risks, and recommended next steps.

---

# 💡 Key Learnings

- Learned the complete hospital admission readiness workflow.
- Understood Prior Authorization decision pathways.
- Explored weighted healthcare readiness scoring.
- Learned how documentation influences admission approval.
- Studied insurance verification and appeal workflows.
- Understood Utilization Review concepts and InterQual/Milliman criteria.
- Built a healthcare simulation using HTML, Tailwind CSS, and Vanilla JavaScript.
- Implemented workflow state management without external storage.
- Improved interactive UI design for healthcare operations.
- Learned how AI can simplify complex healthcare administration processes.

---

# 📂 Files Included

- Hospital_Admission_Readiness_Simulator.html - [admission_simulator.html](https://github.com/user-attachments/files/30220495/admission_simulator.html)

- Screenshots - <img width="1919" height="868" alt="Screenshot 2026-07-21 143153" src="https://github.com/user-attachments/assets/6b4d5482-fa11-4bd3-8e5f-b2dc57cc097e" />
<img width="1394" height="870" alt="Screenshot 2026-07-21 143226" src="https://github.com/user-attachments/assets/d23e5ece-2dca-4089-acf6-040f3d94e90d" />
<img width="1312" height="821" alt="Screenshot 2026-07-21 143241" src="https://github.com/user-attachments/assets/672cafb5-7b23-4787-b466-fcc83d0eff20" />

<img width="1286" height="859" alt="Screenshot 2026-07-21 143258" src="https://github.com/user-attachments/assets/6b144aed-cde9-4e40-b680-e9675b83249c" />



---

# ✅ Conclusion

This project demonstrates how AI can simplify hospital admission planning by combining workflow automation, readiness scoring, risk assessment, and care coordination into an interactive learning experience. It strengthened my understanding of healthcare operations while improving my frontend development and problem-solving skills.
