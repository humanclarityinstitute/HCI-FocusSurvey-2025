# Focus and Distraction 2025 (Dataset, n = 790)

A cross-sectional survey examining how digital notifications, multitasking, and modern online environments influence attention stability, perceived cognitive strain, and behavioural alignment within digitally mediated life.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17394086.svg)](https://doi.org/10.5281/zenodo.17394086)

**Latest version:** v2.1 — 2026-02-17  
**License:** CC-BY-4.0  

**Dataset page:**  
https://humanclarityinstitute.com/datasets/focus-distraction-2025/

**Data summary page:**  
https://humanclarityinstitute.com/data/focus-distraction-2025/

---

## 1. Overview

This dataset examines:

- Sustained attention capacity in digitally fragmented environments  
- Subjective cognitive strain and perceived overload  
- Behavioural alignment with personal values under distraction  
- Perceived impact of distraction on meaning and productivity  

Designed for:

- Cross-dataset comparison  
- Foundational construct lineage mapping  
- Human Reference Layer (HRL) integration  

Part of the **Human–AI Experience 2025 Series** published by the Human Clarity Institute (HCI).

This dataset forms part of the Human Clarity Institute’s longitudinal measurement library and is aligned with the Human Reference Layer (HRL) and Construct Registry framework.

---

## 2. Files Included

| Filename | Description |
|----------|------------|
| **HCI_focus_distraction_2025_raw.csv** | Raw dataset (PII removed). Original column order; no transformations applied. |
| **HCI_focus_distraction_2025_clean.csv** | Clean, machine-readable dataset with canonical tokens and standardised formats. |
| **HCI_focus_distraction_2025_data_dictionary.csv** | Full variable dictionary including definitions, types, allowed values, and construct mapping. |
| **sha256.txt** | SHA-256 checksums for all files in this release. |
| **HCI_focus_distraction_2025_README.md** | Dataset documentation (this file). |

---

## 3. Provenance & Data Collection

Data collected on **3 September 2025** via **Prolific** as part of the Human Clarity Institute research programme.

Participants provided explicit consent for anonymised open publication.

### Sampling & Quality Controls

- **Final n:** 790  
- **Countries:** United Kingdom, United States, Canada, Australia, Ireland, New Zealand  
- **Eligibility:** Adults (18+) fluent in English  
- **Compensation:** £21.18/hr average reward rate  
- **Anonymisation:** Participant IDs, timestamps, and indirect identifiers removed prior to release  

Six duplicate submissions were identified and removed during cleaning (796 → 790). Only the first valid submission per participant was retained.

---

## 4. Data Structure

The full variable structure is provided in the accompanying data dictionary.

Variable types include:

- Single-select categorical variables  
- Multi-select canonical token variables  
- Open-text reduced thematic variables  
- Standard demographic variables  

All variable names use `snake_case` and follow HCI canonical naming standards.

---

### Multi-Select Formatting

Multi-select variables are stored as semicolon-delimited canonical tokens.

Example:

`social_media;notifications;multitasking`

---

### Open-Text Reduction Method

The three open-text value questions were coded into canonical thematic categories following minimal cleaning (trim + newline removal). Raw participant wording is not included in these reduced variables.

---

## 4A. Construct Mapping & Longitudinal Role

### Primary Constructs
- attention_capacity  
- cognitive_load  

### Secondary Constructs
- behavioural_alignment  
- meaning_coherence  

### Anchor Variables
No Standardised Era anchor variables are declared for this dataset. Foundational Era variables are mapped for lineage clarity only.

### Spine Variables
None formally declared for this dataset.

### HRL Domains
- Attention & Cognitive Load  
- Meaning & Behavioural Alignment  

### Longitudinal Role
Foundational Extension (Pre-Standardised Era)

This dataset functions as a foundational construct development dataset within the HCI longitudinal framework. Variables are mapped for lineage clarity but do not constitute Standardised Era anchor declarations.

---

## Interpretation Limits

- This dataset is cross-sectional and reflects responses collected at a single point in time.
- All measures are self-reported and subject to perception and recall bias.
- Findings describe statistical distributions at the group level only.
- Results must not be used for individual-level inference, diagnosis, or assessment.
- No causal, predictive, or normative conclusions should be drawn.

This dataset is designed for descriptive and comparative analysis within the HCI measurement architecture.

---

## 5. Related Datasets

| Dataset | DOI |
|----------|------|
| Digital Life 2025 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17393880.svg)](https://doi.org/10.5281/zenodo.17393880) |
| Cognitive Load, Fatigue & Decision Offloading 2025 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17636370.svg)](https://doi.org/10.5281/zenodo.17636370) |
| Attention & Focus under Digital Load 2026 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18617930.svg)](https://doi.org/10.5281/zenodo.18617930) |

---

## 6. Related Reports

- Why Can’t I Focus?  
  https://humanclarityinstitute.com/reports/why-cant-i-focus-full-report/

- Values vs Noise  
  https://humanclarityinstitute.com/reports/values-vs-noise-full-report/

---

## 7. License

This dataset is released under the **Creative Commons CC-BY-4.0 License**.

You may copy, modify, distribute, or build upon the material for any purpose, including commercial use, provided appropriate credit is given.

---

## 8. Recommended Citation

### APA

Human Clarity Institute. (2025). *Focus and Distraction 2025 (Dataset).* https://doi.org/10.5281/zenodo.17394086

### BibTeX

    @dataset{hci_focus_distraction_2025,
      author    = {Human Clarity Institute},
      title     = {Focus and Distraction 2025 (Dataset)},
      year      = {2025},
      publisher = {Zenodo},
      version   = {v2.1},
      doi       = {10.5281/zenodo.17394086},
      url       = {https://doi.org/10.5281/zenodo.17394086}
    }

---

## 9. Version History

| Version | Date | Change |
|---------|------------|---------|
| v2.1 | 2026-02-17 | Construct mapping added; registry alignment clarified; filenames standardised. |
| v2.0 | 2025-12-11 | Machine-readable upgrade; canonical tokens; dictionary added. |
| v1.0 | 2025-09-03 | Initial publication. |

---

## 10. About the Human Clarity Institute

The Human Clarity Institute (HCI) is an independent research institute documenting the human experience of the AI era through open, longitudinal behavioural datasets.

Website: https://humanclarityinstitute.com  
Contact: info@humanclarityinstitute.com
