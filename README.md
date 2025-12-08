# Human Values, Purpose & Meaning 2025 (Dataset, n = 507)

A cross-sectional dataset examining how adults understand their personal values, sense of meaning, fulfilment, behaviour alignment, and emotional wellbeing — and how these relate to digital environments and AI-mediated life.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17705733.svg)](https://doi.org/10.5281/zenodo.17705733)

**Latest version:** v4 — 2025-12-09  
**License:** CC-BY-4.0

**Dataset page:**  
https://humanclarityinstitute.com/datasets/human-values-purpose-meaning-2025/

**Data summary page:**  
https://humanclarityinstitute.com/data/human-values-purpose-meaning-data-2025/

**Dashboard:**  
https://humanclarityinstitute.com/data-dashboard/

---

## Key Features

- 20+ scale items on meaning, fulfilment, direction, purpose, value alignment, and self-trust  
- Multi-select indicators of top personal values and areas least aligned with one’s values  
- Open-text reflections on core values and what matters most in life  
- Fully cleaned, canonical multi-select tokens and standardised variable naming  
- Part of the **Human–AI Experience 2025** longitudinal data series

---

## Files Included

| Filename | Description |
|---------|-------------|
| **Human_values_purpose_meaning_raw20251125.csv** | Raw dataset (PII removed). Original column order; no transformations applied. |
| **Human_values_purpose_meaning_clean20251125.csv** | Clean, machine-readable dataset. Canonical tokens, standardised multi-selects, minimal text cleaning. |
| **Human_values_purpose_meaning_dictionary.csv** | Full variable dictionary with definitions, types, and allowed values. |
| **sha256.txt** | SHA-256 checksums for all files in this release (raw, clean, dictionary, README). |
| **README.md** | Documentation describing dataset purpose, provenance, file structure, and citation. |

---

## Provenance & Data Collection

Data collected on **25 November 2025** via **Prolific** as part of the Human Clarity Institute’s Human–AI Experience research programme.  
Participants provided **explicit consent** for anonymised open publication.

### Sampling & Quality Controls

- **Final n:** 507  
- **Countries:** UK, US, New Zealand, Ireland, Canada, Australia  
- **Eligibility:** Adults 18+, fluent English  
- **Compensation:** Approx. £10.55/hour (GBP)  
- **Approval-rate filter:** None  
- **Attention checks:** None  
- **AI-deception traps:** None  
- **Anonymisation:** Prolific IDs and timestamps removed before publication  

---

## Data Structure (Summary)

| Variable | Type | Description |
|----------|------|-------------|
| `values_top3_multi` | multi_select | Three most important personal values (canonical tokens). |
| `values_misaligned_areas_multi` | multi_select | Areas of life least aligned with personal values. |
| `what_matters_most` | open_text | Free-text reflection on what matters most in life. |
| `life_direction` | numeric | Sense of clarity and direction in life (1–7). |
| `ai_values_multi` | multi_select | Values participants believe AI systems should follow. |
| ... | ... | See full dictionary for all variables. |

**Multi-select formatting:**  
Stored as semicolon-delimited canonical tokens, e.g.:

```
family;health;responsibility
```

**Open-text fields:**  
Minimal cleaning applied (trim + newline removal).  
Raw participant meaning preserved exactly.

---

## Related Datasets (Human–AI Experience 2025 Series)

| Dataset | DOI Badge |
|--------|-----------|
| **Digital Life 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17393880.svg)](https://doi.org/10.5281/zenodo.17393880) |
| **Focus & Distraction 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17394087.svg)](https://doi.org/10.5281/zenodo.17394087) |
| **Emotion, Identity & Creativity in the Age of AI 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17653906.svg)](https://doi.org/10.5281/zenodo.17653906) |
| **Digital Trust 2025** | [![DOI](https://zenodo.org/badge/DOI/https://doi.org/10.5281/zenodo.17717450.svg)](https://doi.org/https://doi.org/10.5281/zenodo.17717450) |
| **AI, Work & Human Identity 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17604671.svg)](https://doi.org/10.5281/zenodo.17604671) |
| **AI-Assisted Decision Making 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17782046.svg)](https://doi.org/10.5281/zenodo.17782046) |

---

## Related Reports

- **Values vs Noise**  
  https://humanclarityinstitute.com/reports/values-vs-noise-full-report/

- **Coping & Wellbeing**  
  https://humanclarityinstitute.com/reports/coping-and-wellbeing-full-report/

- **Values Discovery**  
  https://humanclarityinstitute.com/reports/values-discovery-full-report/


---

## License

This dataset is released under the **Creative Commons CC-BY-4.0 License**.  
You may copy, modify, distribute, or build upon the material for any purpose, including commercial use, provided appropriate credit is given.

---

### **APA**
Human Clarity Institute. (2025). *Human Values, Purpose & Meaning 2025 (Dataset).* https://doi.org/10.5281/zenodo.17705733

### **BibTeX**
```bibtex
@dataset{hci_human_values_purpose_meaning_2025,
  author    = {Human Clarity Institute},
  title     = {Human Values, Purpose \& Meaning 2025 Dataset},
  year      = {2025},
  publisher = {Human Clarity Institute},
  doi       = {10.5281/zenodo.17705733},
  url       = {https://humanclarityinstitute.com/datasets/human-values-purpose-meaning-2025/},
  license   = {CC-BY-4.0}
}
```

## Version History

| Version | Date | Change |
|---------|------------|---------|
| v4 | 2025-12-09 | Structural improvements to README layout; improved machine readability |
| v1.1 | 2025-12-04 | Removed Prolific IDs; file replacements |
| v1.0 | 2025-11-25 | Initial release |

---

## Contact

For questions, collaboration opportunities, or media enquiries:

- **Website:** https://humanclarityinstitute.com  
- **Email:** info@humanclarityinstitute.com  

Human Clarity Institute (HCI) — documenting the human experience of the AI era.
