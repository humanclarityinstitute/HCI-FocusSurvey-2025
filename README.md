# Focus and Distraction 2025 (Dataset, n = 790)

A global dataset capturing how digital notifications, multitasking, and modern online environments influence people’s ability to focus, sustain attention, and complete tasks.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17394086.svg)](https://doi.org/10.5281/zenodo.17394086)

**Latest version:** V2.0 — 2025-12-11  
**License:** CC-BY-4.0

**Dataset page:**  
https://humanclarityinstitute.com/datasets/focus-distraction-2025/

**Data summary page:**  
https://humanclarityinstitute.com/data/focus-distraction-2025/

**Dashboard:**  
https://humanclarityinstitute.com/data-dashboard/

---

## Key Features

- Cleaned, machine-readable focus and distraction metrics  
- Canonical multi-select attention and behaviour variables  
- Open-text explanations of personal focus challenges  
- Demographic and digital-exposure indicators across six countries  
- Part of the **Human–AI Experience 2025** longitudinal data series

---

## Files Included

| Filename | Description |
|---------|-------------|
| **Focus_distraction_2025_raw20251112.csv** | Raw dataset (PII removed). Original column order; no transformations applied. |
| **Focus_distraction_2025_clean20251112.csv** | Clean, machine-readable dataset. Canonical tokens, standardised multi-selects, minimal text cleaning. |
| **Focus_distraction_2025_data_dictionary.csv** | Full variable dictionary with definitions, types, and allowed values. |
| **sha256.txt** | SHA-256 checksums for all files in this release (raw, clean, dictionary, README). |
| **README.md** | Documentation describing dataset purpose, provenance, file structure, and citation. |

---

### Provenance & Data Collection

Data collected on **3 September 2025** via **Prolific** as part of HCI’s Human–AI Experience research programme.  
Participants provided **explicit consent** for anonymised open publication.

### Sampling & Quality Controls

- **Final n:** 790  
- **Countries:** UK, USA, Canada, Australia, Ireland, New Zealand  
- **Eligibility:** Adults 18+, fluent English  
- **Compensation:** £21.18/hr average reward rate  
- **Approval-rate filter:** Minimum approval rating required (standard Prolific prescreen)  
- **Anonymisation:** All Prolific IDs, timestamps, and indirect identifiers removed before publication  

---

### Data Cleaning Notes

During cleaning, **6 duplicate submissions** were identified and removed from the raw dataset (796 → 790).  
Only the **first valid submission** for each affected participant was retained.  
No other exclusions were applied.

---

### Open-Text Reduction Method (Applied to Final Three Value Items)

To preserve meaning while ensuring machine-readability, the three open-text “values” questions were coded into the **6–8 most commonly occurring thematic categories**.  
This reduction was applied *after* initial cleaning (trim + newline removal).  
Raw participant wording is **not** included in these variables; each response is mapped to a **canonical theme label** for consistent analysis.

---

## Data Structure (Summary)

| Variable | Type | Description |
|----------|------|-------------|
| focus_duration_single_task | categorical | Self-reported duration participants can stay focused on a single task (e.g., less than 5 minutes, 5–10 minutes, 11–20 minutes, etc.). |
| main_distractions_multi | multi-select | Canonical tokens representing participants’ primary sources of digital distraction. Stored as semicolon-delimited values. |
| lose_focus_feeling_one_word | open-text | Participant-describe how they feel when they loose focus. |

**Multi-select formatting:**  
Stored as semicolon-delimited canonical tokens, e.g.:

`social_media;notifications;multitasking`

**Open-text fields:**  
Minimal cleaning applied (trim + newline removal).  
Raw participant meaning preserved exactly.

---

## Related Datasets (Human–AI Experience 2025 Series)


| Dataset | DOI Badge |
|--------|-----------|
| **Digital Life 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17393880.svg)](https://doi.org/10.5281/zenodo.17393880) |
| **Human Values, Purpose & Meaning 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17705733.svg)](https://doi.org/10.5281/zenodo.17705733) |
| **Digital Trust 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17717450.svg)](https://doi.org/10.5281/zenodo.17717450) |
| **Emotion, Identity & Creativity in the Age of AI 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17653906.svg)](https://doi.org/10.5281/zenodo.17653906) |
| **AI Safety, Risk Perception & Boundary Behaviour 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17782046.svg)](https://doi.org/10.5281/zenodo.17782046) |

---

## Related Reports

- **Why Can’t I Focus?**  
  https://humanclarityinstitute.com/reports/why-cant-i-focus-full-report/

- **Values vs Noise**  
  https://humanclarityinstitute.com/reports/values-vs-noise-full-report/

---

## License

This dataset is released under the **Creative Commons CC-BY-4.0 License**.  
You may copy, modify, distribute, or build upon the material for any purpose, including commercial use, provided appropriate credit is given.

---

## Recommended Citation

### **APA**
Human Clarity Institute. (2025). *Focus and Distraction 2025 (Dataset).* https://doi.org/10.5281/zenodo.17394086

### **BibTeX**
    @dataset{hci_focus_distraction_2025,
      author       = {Human Clarity Institute},
      title        = {Focus and Distraction 2025 (Dataset)},
      year         = {2025},
      publisher    = {Zenodo},
      version      = {V2.0},
      doi          = {10.5281/zenodo.17394086},
      url          = {https://doi.org/10.5281/zenodo.17394086}
    }

---

## Version History

| Version | Date | Change |
|---------|------------|---------|
| V2.0 | 2025-12-11 | Upgraded to machine-readable standard; added canonical tokens; added dictionary; updated README. |
| v1.1 | PLACEHOLDER_PREV_DATE_1 | Removed Prolific IDs; file replacements |
| v1.0 | PLACEHOLDER_PREV_DATE_0 | Initial release |

---

## Contact

For questions, collaboration opportunities, or media enquiries:

- **Website:** https://humanclarityinstitute.com  
- **Email:** info@humanclarityinstitute.com  

HCI is an independent research institute documenting the human experience of the AI era.
