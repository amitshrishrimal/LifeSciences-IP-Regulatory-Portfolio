# Adverse Drug Reaction (ADR) Signal Detection Dashboard Logic
**Author:** [Amit Shrishrimal / Pharmacist]

This document outlines the data architecture, metrics, and risk-assessment logic utilized to build a functional Pharmacovigilance (PV) dashboard. It maps clinical safety data to actionable insights for signal detection and regulatory reporting.

## 1. Dashboard Objective
To aggregate post-marketing and clinical trial safety reports, allowing safety teams to detect unexpected trends, calculate reporting frequencies, and assess causal relationships between drugs and adverse events.

## 2. Core Safety Metrics & KPIs Monitored
*   **Total ICSRs (Individual Case Safety Reports):** Count of unique patient safety cases received.
*   **Serious vs. Non-Serious Ratio:** Percentage of cases classified as "Serious" based on regulatory definitions (Death, Life-threatening, Hospitalization, Disability, Congenital Anomaly).
*   **Listed vs. Unlisted Events:** Distribution of events checked against the Company Core Data Sheet (CCDS) or Reference Safety Information (RSI).
*   **Dechallenge / Rechallenge Matrix:** Count of positive, negative, or ambiguous patient responses upon drug discontinuation or reintroduction.

## 3. Signal Detection Logic & Algorithms
The dashboard framework relies on established causality assessment models to flag high-risk signals:

### Naranjo Algorithm Scoring Interface
The system categorizes causality based on user inputs matching the Naranjo scale:
*   **Score ≥ 9:** Definite ADR
*   **Score 5–8:** Probable ADR
*   **Score 1–4:** Possible ADR
*   **Score ≤ 0:** Doubtful ADR

### Proportional Reporting Ratio (PRR) Calculation
To screen for statistical signals, the background pipeline implements the standard PRR formula comparing the proportion of a specific ADR for a specific drug against all other drugs in the safety database.
