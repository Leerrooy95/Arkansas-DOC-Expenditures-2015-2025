# Arkansas Division of Correction Expenditures, FY2015–FY2025

A data-driven compilation of official expenditure figures published by the Arkansas Division of Correction (ADC) and Division of Community Correction (ACC), extracted from 287 state reports.

**Full source archive**: [Zenodo — DOI: 10.5281/zenodo.17663528](https://zenodo.org/records/17663528)

---

## Table of Contents
- [Quick Summary](#quick-summary)
- [Ten-Year Expenditure Trend](#ten-year-expenditure-trend)
- [Key Context](#key-context)
- [Revenue Offsets (FY2024)](#revenue-offsets-fy2024)
- [Repository Contents](#repository-contents)
- [Data Verification](#data-verification)
- [Methodology](#methodology)
- [Connected Repositories](#connected-repositories)
- [Limitations & Disclaimer](#limitations--disclaimer)
- [License & Contact](#license--contact)

---

## Quick Summary

**Total documented ADC spending across ten fiscal years: $3.92 billion** (FY2015–FY2024, ADC only; combined ADC + ACC total across all available data: $4.19 billion)

**FY2024 total expenditures: $469,289,163**
— ADC FY24 Annual Report, page 8 ✅ Verified

This figure is notable because it approaches the estimated cost of the proposed new 3,000-bed Franklin County prison ($825 million) — meaning Arkansas spent more than half the total construction cost in a single year of operations alone.

---

## Ten-Year Expenditure Trend

All figures are sourced directly from ADC annual reports. No external estimates or modeling were used.

| Fiscal Year | Total Expenditures | YoY Change |
|-------------|-------------------|------------|
| 2024 | **$469,289,163** | +8.0% |
| 2023 | $434,337,302 | +4.0% |
| 2022 | $417,506,575 | +6.5% |
| 2021 | $392,181,404 | +3.1% |
| 2020 | $380,489,377 | +1.4% |
| 2019 | $375,058,996 | +2.4% |
| 2018 | $366,102,656 | +0.1% |
| 2017 | $365,782,232 | +0.5% |
| 2016 | $363,825,884 | +1.1% |
| 2015 | $359,869,988 | — |
| **Total** | **$3,924,443,577** | **+30.4% over decade** |

*Compound annual growth rate (CAGR): 3.0%*

---

## Key Context

| Metric | Value | Source |
|--------|-------|--------|
| FY2024 ADC expenditures | $469,289,163 | ADC FY24 Annual Report, p. 8 |
| Proposed new prison (Franklin County) | $825 million (3,000 beds) | Arkansas DOC / SB354 (2025) |
| Arkansas incarceration rate | 912 per 100,000 (3rd in U.S.) | Prison Policy Initiative |
| State prison population | 17,000+ | Multiple sources (2024) |
| County jail backup (state inmates) | ~1,663/month avg | ADC Director's Board Report (Dec 2023) |
| County jail reimbursement (FY24–25) | $27.7 million | Arkansas Advocate (Dec 2025) |

---

## Revenue Offsets (FY2024)

| Revenue Source | Amount | % of Total Budget |
|----------------|--------|-------------------|
| Inmate agricultural production | $5.06 million | 1.1% |
| Industry + work-release revenue | $13.8 million | 2.9% |
| **Combined offsets** | **$18.86 million** | **4.0%** |

**Taxpayers funded more than 96%** of the FY2024 total.

---

## Repository Contents

```
Arkansas-DOC-Expenditures-2015-2025/
├── README.md                                  # This file
├── Arkansas_DOC_Financials_FULL_2025.csv       # 29,337 extractions from 287 reports
├── FY24-Annual-Report-FINAL.pdf               # Official source of the $469M figure
├── sources.txt                                # Contact for full 8 GB archive of 287 PDFs
└── Copilot_Opus_4.6_Analysis/                 # Independent verification workstation
    ├── README.md                              # Workstation overview and methodology
    ├── Verification_Reports/                  # Source cross-checks and data validation
    │   └── core_data_verification.md          # ✅ All core claims verified
    └── Archive/                               # Original image files (preserved, not deleted)
```

---

## Data Verification

All core expenditure figures have been independently verified. See [`Copilot_Opus_4.6_Analysis/Verification_Reports/core_data_verification.md`](Copilot_Opus_4.6_Analysis/Verification_Reports/core_data_verification.md) for the full report.

| Claim | Status |
|-------|--------|
| FY2024 total: $469,289,163 | ✅ Verified (ADC FY24 Annual Report, p. 8) |
| Ten-year ADC sum: $3.92 billion | ✅ Arithmetic verified |
| Proposed prison cost: $825 million | ✅ Verified (DOC, Arkansas Advocate, KATV) |
| Revenue offsets: ~4% of budget | ✅ Verified (FY24 Annual Report) |
| Dataset: 29,337 rows from 287 reports | ✅ Verified |

### Independent Corroboration

The [Arkansas Advocate](https://arkansasadvocate.com/) began covering Arkansas prison costs in December 2025 — one month after this repository was created — with figures consistent with this analysis:

- **Dec 17, 2025**: ["Overcrowded: Arkansas' prison system costs inmates, taxpayers"](https://arkansasadvocate.com/2025/12/17/overcrowded-arkansas-prison-system-costs-inmates-taxpayers/)
- **Dec 19, 2025**: ["Overcrowded: Protect Arkansas Act to drive continued prison population growth"](https://arkansasadvocate.com/2025/12/19/overcrowded-protect-arkansas-act-to-drive-continued-prison-population-growth-for-at-least-a-decade/)

---

## Methodology

1. **Source documents**: 287 official PDF reports published by the Arkansas Division of Correction (FY2015–FY2025), obtained from [doc.arkansas.gov](https://doc.arkansas.gov/)
2. **Extraction**: OCR-based text extraction producing 29,337 structured rows
3. **Verification**: Key figures cross-checked against official annual reports and independent news coverage
4. **Transparency**: Full 8 GB archive of all 287 source PDFs preserved on [Zenodo](https://zenodo.org/records/17663528) for reproducibility

---

## Connected Repositories

| Repository | Focus |
|-----------|-------|
| [Arkansas-Department-of-Corrections-2015-2025-Timeline](https://github.com/Leerrooy95/Arkansas-Department-of-Corrections-2015-2025-Timeline) | Monthly population/death time series, statistical analysis of March surges and post-parole mortality |
| [The_Regulated_Friction_Project](https://github.com/Leerrooy95/The_Regulated_Friction_Project) | Data-driven analysis of temporal correlations between friction events, policy shifts, and capital flows (includes state-level Arkansas regulatory capture analysis) |

---

## Limitations & Disclaimer

- All data consists of **public records** published by the Arkansas Department of Corrections. No external estimates or modeling were used.
- The CSV dataset was produced via OCR extraction from scanned PDFs. While key figures have been verified, individual row-level accuracy may vary due to OCR artifacts in the source documents.
- Expenditure figures in the ten-year table represent ADC (Division of Correction) only. The combined ADC + ACC (Division of Community Correction) total across all available data is approximately $4.19 billion.
- This repository documents spending patterns. It does not make claims about policy intent or institutional motivation.

---

## License & Contact

**License**: CC0 1.0 — Public Domain. Use and share freely.

**Prepared by**: Austin Smith
U.S. Army 19D Veteran | Former Arkansas Correctional Officer
November 2025

**Contact**: See `sources.txt`

**GitHub**: [@Leerrooy95](https://github.com/Leerrooy95)
