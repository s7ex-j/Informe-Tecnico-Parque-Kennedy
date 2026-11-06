# Technical Report: Physicochemical Characterization of Urban Soils in Parque Kennedy

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21695655.svg)](https://doi.org/10.5281/zenodo.21695655)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-blue.svg)](https://creativecommons.org/licenses/by/4.0/)
[![LaTeX](https://img.shields.io/badge/LaTeX-jaes.cls-orange.svg)](Informe/Informe.tex)

<sub>[Español](README.md) · **English**</sub>

**Author:** Jharol André Vilca Ramos  
**ORCID:** [0009-0009-7897-3439](https://orcid.org/0009-0009-7897-3439)  
**Affiliation:** Universidad Privada del Norte, Faculty of Industrial Engineering, Lima, Peru  
**Date:** June 2026  
**License (code):** MIT  
**License (document archived on Zenodo):** CC-BY-4.0  
**DOI (Zenodo):** [10.5281/zenodo.21695655](https://doi.org/10.5281/zenodo.21695655)

> The report itself is written in Spanish.

---

## 📋 Project description

This repository contains the full technical report on the **physicochemical characterization of urban soils** carried out in **Parque Kennedy** (Miraflores, Lima, Peru). The study evaluates how the intense biogenic activity associated with a large cat population affects the properties of the urban soil.

### Objectives
- Determine the baseline physicochemical properties of the urban soil
- Evaluate the influence of continuous biogenic inputs (cat excreta) on soil salinization
- Build a reference dataset for urban soil studies in Lima

### Context
Parque Kennedy has unusual conditions: intensive recreational use, a high density of feral/domestic cats, and calcareous coastal soils. This combination drives **soil salinization** and organic matter accumulation that are atypical for standard urban parks.

---

## 📊 Main results

| Parameter | Value | Interpretation |
|-----------|-------|----------------|
| **Gravimetric moisture** | 23.10% ± 0.39% | Moderate-to-high water content |
| **Bulk density** | 1.61 ± 0.05 g/cm³ (air-dried) | Moderate compaction from recreational use |
| **pH** | 7.09 ± 0.03 | Neutral, coastal calcareous buffer |
| **pH temperature** | 22.73 ± 0.12 °C | Standardized measurement conditions |
| **Electrical conductivity** | **1970 ± 60 μS/cm** | **⚠️ Anomalous** (standard < 500 μS/cm) |
| **Texture** | Sandy loam (~73% sand, ~24% fines) | Good drainage, low retention |
| **Organic matter (LOI at 505°C)** | 3.94% | Upper end of the regional range |

### Key finding
**Electrical conductivity (1970 μS/cm)** is about 4× the typical value for urban parks (< 500 μS/cm), consistent with soluble salt accumulation from **continuous biogenic inputs** (cat excreta). The neutral pH reflects the calcareous buffering capacity of Lima's coastal soils.

---

## 📁 Repository structure

```
Informe-Tecnico-Parque-Kennedy/
├── LICENSE
├── CITATION.cff
├── README.md
├── Informe/
│   ├── Informe.tex          # Main LaTeX source
│   ├── jaes.cls             # JAES document class
│   ├── jaes.bib             # Bibliography
│   ├── jaes.bst             # Bibliography style
│   ├── Informe.pdf          # Compiled PDF (version archived on Zenodo)
│   ├── cuted.sty            # Package for mixed columns
│   └── orcidlink.sty        # Package for ORCID links
├── Imágenes/
│   ├── Macrolocalización.pdf
│   ├── Microlocalización.pdf
│   ├── Plano vial de Carreteras.pdf
│   ├── Capa Cartográfica (AutoCAD).pdf
│   ├── Capa Georreferenciada.pdf
│   └── Punto de muestreo.pdf
└── Entregables/
    ├── Ficha_Muestreo.xlsx
    └── Plan de muestreo.docx
```

---

## 🛠️ How to compile the report

**Requirements:** LaTeX (TeX Live / MiKTeX) with `latexmk`, standard packages + the included `jaes.cls`.

```bash
cd Informe
latexmk -pdf Informe.tex
```

The generated PDF (`Informe.pdf`) is identical to the one archived on Zenodo (DOI: 10.5281/zenodo.21695655).

---

## 📖 Methodology summary

1. **Sampling**: Composite sample, reduced by standardized quartering (NTP 339.089)
2. **Gravimetric moisture**: Drying at 105 °C to constant weight (NTP 339.127)
3. **Bulk density**: Volumetric cylinder method (ASTM D7263) on fine earth
4. **pH**: Potentiometry in a 1:2.5 (soil:water) suspension per ISO 10390
5. **Electrical conductivity**: 1:2.5 soil-water suspension (NTP-ISO 11265) — **not** a saturation extract
6. **Texture**: Dry mechanical sieving with a series of 8 sieves (NTP 339.128) — **not** Bouyoucos/hydrometer
7. **Organic matter**: Loss on ignition (LOI) at **505°C** — **not** 440°C

---

## 📄 How to cite

If you use this work, please cite it as:

```bibtex
@techreport{VilcaRamos2026,
  author       = {Vilca Ramos, Jharol André},
  title        = {Informe Técnico: Caracterización Fisicoquímica de Suelos Urbanos del Parque Kennedy},
  institution  = {Universidad Privada del Norte, Facultad de Ingeniería Industrial},
  year         = {2026},
  month        = {6},
  doi          = {10.5281/zenodo.21695655},
  url          = {https://github.com/s7ex-j/Informe-Tecnico-Parque-Kennedy},
  type         = {Informe Técnico}
}
```

Or use the `CITATION.cff` file for automatic citation on GitHub/Zenodo.

---

## 📜 Licenses

| Component | License |
|------------|----------|
| Code / scripts / LaTeX source | [MIT](LICENSE) |
| Archived PDF document (Zenodo) | [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/) |

---

## 🔗 Related links

- **Zenodo (archived version):** https://doi.org/10.5281/zenodo.21695655
- **GitHub repository:** https://github.com/s7ex-j/Informe-Tecnico-Parque-Kennedy
- **Author ORCID:** https://orcid.org/0009-0009-7897-3439
