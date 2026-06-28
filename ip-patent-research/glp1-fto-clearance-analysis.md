# Freedom to Operate (FTO) Search & Patent Clearance Portfolio
**Project Focus:** Next-Generation GLP-1/GIP Dual Agonist Formulation  
**Prepared By:** [Amit Shrishrimal B.Pharm]  
**Date:** June 2026  
**Status:** Completed Search & Initial Clearance Mapping  

---

## 1. Executive Summary
This FTO portfolio simulates an industry-standard patent clearance risk analysis for a fictional, fast-dissolving oral tablet formulation of a **GLP-1/GIP dual receptor agonist** (Target Compound: "G-102"). The objective is to identify potential patent barriers in primary jurisdictions prior to advancing to Phase I clinical trials. 

### Clearance Status Summary
*   **Active Ingredients (API):** Low Risk (Core compound patents in the target class expire by 2028).
*   **Formulation/Delivery System:** Medium Risk (High density of active patents surrounding oral permeation enhancers like SNAC).
*   **Overall Clearance Strategy:** Clearance via **Design-Around** of specific excipient weight ratios and utilization of open-access chemical delivery systems.

---

## 2. Search Strategy & Scope
A rigorous, multi-tiered search strategy was executed across global patent databases to maximize recall of relevant pharmaceutical claims.

### Database Parameters
*   **Databases Searched:** USPTO (Patent Public Search), EPO (Espacenet), WIPO (Patentscope).
*   **Date Constraints:** January 1, 2006 – Present (Capturing the 20-year statutory patent lifecycle).
*   **Geographic Scope:** United States (US), European Patent Office (EP), and PCT International applications.

### Patent Classification Filters (CPC/IPC)
*   **A61K 38/26:** Peptides; Glucagon-like peptides (GLP-1).
*   **A61K 9/20:** Solid oral dosage forms; Tablets.
*   **A61P 3/04:** Anti-obesity agents.

### Boolean Search Queries
```text
(GLP-1 OR "glucagon-like peptide") AND (GIP OR "gastric inhibitory polypeptide") AND (oral* OR tablet* OR capsule*) AND (permeation OR absorption ENHANCER) AND (weight OR obesity)
```

---

## 3. High-Risk Patent Landscape & Claims Mapping
The search retrieved 142 results. Screening narrowed the pool to two high-risk active patent families with independent claims that structurally overlap with our target formulation.

### Patent Reference 1: US 10,945,123 B2 (Active)
*   **Assignee:** Global Biopharma Corp
*   **Expiration Date:** August 14, 2034
*   **Relevant Independent Claim:** 
    > *"Claim 1: A solid oral pharmaceutical composition comprising: (a) 1–10 mg of a GLP-1/GIP dual co-agonist peptide; and (b) a delivery enhancer comprising sodium N-(8-[2-hydroxybenzoyl]amino)caprylate (SNAC), wherein the weight ratio of peptide to SNAC is between 1:20 and 1:50."*
*   **Infringement Risk Analysis:** **HIGH RISK**. Our prototype formulation currently utilizes an oral delivery enhancer matrix with a peptide-to-SNAC weight ratio of 1:30, which falls directly within the literal scope of Claim 1.

### Patent Reference 2: EP 3,412,789 A1 (Granted / Active)
*   **Assignee:** Euro-Diabetes Innovations
*   **Expiration Date:** November 23, 2037
*   **Relevant Independent Claim:**
    > *"Claim 1: An oral multi-layered tablet configuration comprising an immediate-release core containing a metabolic peptide agonist and an enteric-coated outer shell containing an effervescent disintegrant variant."*
*   **Infringement Risk Analysis:** **LOW RISK**. While our formulation is a fast-dissolving tablet, it utilizes a homogeneous, single-layer matrix rather than a multi-layered configuration. It completely lacks an enteric-coated outer shell, bypassing literal infringement.

---

## 4. IP Risk Mitigation & Design-Around Strategy
To establish a clear path to commercialization and achieve true "Freedom to Operate," the following formulation engineering modifications are implemented based on the claims mapping data:
### Technical Implementation Steps
1.  **Excipient Threshold Alteration:** Adjust the formulation processing parameters to increase the delivery enhancer density, locking the peptide-to-SNAC weight ratio strictly at **1:65**. This successfully steps outside the literal boundary of US 10,945,123 B2.
2.  **Excipient Substitution:** Initiate parallel stability testing using *Sodium Caprate* instead of SNAC, exploiting a clean whitespace identified in the secondary search cluster.

---

## 5. Methodological Framework (McKinsey Forward Application)
*   **MECE Issue Tree Structuring:** The entire clearance process was segmented into mutually exclusive domains (API, Excipients, Manufacturing Process, Clinical Indication) ensuring zero overlapping variables during patent landscape indexing.
*   **Pyramid Communication:** The risk metrics are tailored for rapid c-suite decision-making, presenting the core legal vulnerability (Formulation ratios) followed by immediate, data-backed chemical synthesis alternatives.
