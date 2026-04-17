# IEP If/Then Scenario Analysis Tool

**A UDL-enhanced, interactive decision framework for high-quality IEP development**

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
[![Status: Active](https://img.shields.io/badge/Status-Active-brightgreen.svg)]()
[![Audience: Special Educators](https://img.shields.io/badge/Audience-Special%20Educators-blue.svg)]()

---

## Overview

This tool presents 23 if/then decision scenarios across six IEP domains, grounded in IDEA (2004), *Endrew F. v. Douglas County School District* (2017), and peer-reviewed special education literature. It was developed as a companion resource to the IRIS Center Module: *IEPs: Developing High-Quality Individualized Education Programs* (iep01).

The tool is built as a single-file HTML application — no frameworks, no dependencies, no server required. It opens directly in any modern browser.

---

## Domains Covered

| Domain | IRIS Module Question | Scenarios |
|--------|---------------------|-----------|
| IEP Definition & Purpose | Q1 | 4 |
| Procedural vs. Substantive Requirements | Q2 | 5 |
| PLAAFP Quality | Q3a | 5 |
| Annual Goal Analysis | Q3b | 5 |
| Statement of Services & Supports | Q3c | 5 |
| Progress Monitoring & Parent Reporting | Q4 | 5 |

---

## UDL Accessibility Features

This tool was designed using Universal Design for Learning (UDL) principles across all three networks:

**Multiple Means of Representation**
- Font size controls (A− / A / A+)
- High contrast mode
- Colorblind-safe mode (pattern- and shape-based risk indicators, no color dependency)
- Expandable detail panels with layered explanations

**Multiple Means of Action and Expression**
- Live keyword search across all 23 scenarios
- Domain filter chips (7 categories)
- Risk level filter chips (High / Medium / Low)
- Collapsible sections with Expand All / Collapse All
- Print-optimized view
- Skip-to-content keyboard navigation link

**Multiple Means of Engagement**
- Read Aloud via Web Speech API (narrates visible scenarios)
- Full ARIA roles, labels, and live regions for screen reader compatibility
- Complete keyboard navigation across all interactive elements

---

## Legal Basis

All scenarios are grounded in primary legal sources and peer-reviewed scholarship:

- Individuals with Disabilities Education Act (IDEA), 20 U.S.C. §§ 1400–1482 (2004)
- *Board of Education v. Rowley*, 458 U.S. 176 (1982)
- *Endrew F. v. Douglas County School District*, 580 U.S. 386 (2017)
- 34 CFR Part 300 (IDEA implementing regulations)
- Bateman, B. D., & Linden, M. A. (2006). *Better IEPs* (4th ed.). Attainment Company.
- National Reading Panel (2000). *Teaching children to read*. NICHD.
- Yell, M. L. (2019). *The law and special education* (5th ed.). Pearson.

---

## Usage

### Option 1: Open locally
Download `index.html` and open it in any modern web browser. No installation required.

### Option 2: Deploy via GitHub Pages
1. Fork or clone this repository
2. Enable GitHub Pages in repository Settings → Pages → Source: main branch
3. The tool will be live at `https://[your-username].github.io/iep-ifthen-chart/`

---

## File Structure

```
iep-ifthen-chart/
├── index.html       # Complete single-file application
├── README.md        # This file
└── LICENSE          # CC BY-NC 4.0 license
```

---

## Validation Notes

All legal citations were validated against primary sources (IDEA statute, CFR regulations, and Supreme Court opinions) prior to publication. Key corrections applied in v3:

- IDEA §1415(f)(3)(E)(ii) three-prong test fully stated (all disjunctive prongs included)
- Prior written notice framing corrected — not an automatic FAPE denial
- 34 CFR §300.320(a)(7) added as co-citation for frequency, duration, and location requirements
- Projected end date correctly identified as common practice, not a federal mandate

---

## License

This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/).

You are free to share and adapt this material for non-commercial purposes with appropriate attribution.

**Attribution format:**
> Wright, C. (2026). *IEP If/Then Scenario Analysis Tool*. Retrieved from https://catrinawright.github.io/iep-ifthen-chart/

**Commercial inquiries:** [cwright.specialed@gmail.com](mailto:cwright.specialed@gmail.com)

---

## Author

**Catrina Wright**
MAT Candidate, LBS1 Endorsement
Chicago Public Schools Teacher Residency Program
National Louis University | Expected Graduation: June 2026

[catrinawright.github.io](https://catrinawright.github.io) · [cwright.specialed@gmail.com](mailto:cwright.specialed@gmail.com)
