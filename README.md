# Phishing Simulation for Students - Thomas More

This repository contains the research and implementation of phishing simulations tailored for students at Thomas More.

## Context
Thomas More ICTS currently utilizes a commercial solution to conduct phishing simulations for staff members. However, there is a need to investigate and test suitable solutions specifically for the students.

## Assignment
The goal of this project is to:
1. **Investigate** the possibility of using the phishing simulation component within **Microsoft 365 Defender**.
2. **Research** and evaluate potential **(free) alternatives** that could be used for student simulations.
3. **Test** the selected solutions and document the process.

---

## Phishing Simulators Overview

The following table lists the simulators identified for evaluation, including their current testing status:

| Tool | Type | Status | Key Characteristics | Documentation |
| :--- | :--- | :--- | :--- | :--- |
| **Microsoft 365 Defender** | Cloud / Integrated | ✅ Tested | Native M365 integration, credential harvesting, automated training. | [View](./m365defender/README.md) |
| **GoPhish** | Open Source | ⏳ To be tested | Highly flexible, self-hosted. | - |
| **Wizer (Free Edition)** | Cloud | ⏳ To be tested | Free edition (10 day trial), limited features. | [View](./wizer/README.md) |
| **CanIPhish** | Cloud | ⏳ To be tested | Managed platform with a free community tier. | [View](./caniphish/README.md) |
