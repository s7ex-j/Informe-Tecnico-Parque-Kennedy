# Informe Técnico: Caracterización Fisicoquímica de Suelos Urbanos del Parque Kennedy

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21695655.svg)](https://doi.org/10.5281/zenodo.21695655)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-blue.svg)](https://creativecommons.org/licenses/by/4.0/)
[![LaTeX](https://img.shields.io/badge/LaTeX-TikZ%20%7C%20pgfplots-orange.svg)]()

**Autor:** Jharol André Vilca Ramos  
**ORCID:** [0009-0009-7897-3439](https://orcid.org/0009-0009-7897-3439)  
**Afiliación:** Universidad Privada del Norte, Facultad de Ingeniería Industrial, Lima, Perú  
**Fecha:** Junio 2026  
**Licencia (código):** MIT  
**Licencia (documento archivado en Zenodo):** CC-BY-4.0  
**DOI (Zenodo):** [10.5281/zenodo.21695655](https://doi.org/10.5281/zenodo.21695655)

---

## 📋 Descripción del Proyecto

Este repositorio contiene el informe técnico completo de la **caracterización fisicoquímica de suelos urbanos** realizada en el **Parque Kennedy** (Miraflores, Lima, Perú). El estudio evalúa el impacto de la intensa actividad biogénica asociada a una elevada población felina sobre las propiedades del suelo urbano.

### Objetivos
- Determinar las propiedades fisicoquímicas baseline del suelo urbano
- Evaluar la influencia de aportes biogénicos continuos (excretas felinas) en la salinización edáfica
- Generar una base de datos de referencia para estudios de suelos urbanos en Lima

### Contexto
El Parque Kennedy presenta condiciones únicas: uso recreativo intensivo, alta densidad de felinos ferales/domésticos, y suelos costeros calcáreos. Esta combinación genera procesos de **salinización edáfica** y acumulación de materia orgánica atípicos para parques urbanos estándar.

---

## 📊 Resultados Principales

| Parámetro | Valor | Interpretación |
|-----------|-------|----------------|
| **Humedad gravimétrica** | 23.10% ± 0.39% | Contenido hídrico moderado-alto |
| **Densidad aparente** | 1.61 ± 0.05 g/cm³ (aire-seca) | Compactación moderada por uso recreativo |
| **pH** | 7.09 ± 0.03 | Neutro, tampón calcáreo costero |
| **Temperatura pH** | 22.73 ± 0.12 °C | Condiciones de medición estandarizadas |
| **Conductividad eléctrica** | **1970 ± 60 μS/cm** | **⚠️ Anómala** (estándar < 500 μS/cm) |
| **Textura** | Franco-arenosa (~73% arena, ~24% finos) | Buen drenaje, baja retención |
| **Materia orgánica (LOI a 505°C)** | 3.94% | Extremo superior rango regional |

### Hallazgo Clave
La **conductividad eléctrica (1970 μS/cm)** es ~4× el valor típico de parques urbanos (< 500 μS/cm), consistente con acumulación de sales solubles por **aportes biogénicos continuos** (excretas felinas). El pH neutro refleja la capacidad tampón calcárea de suelos costeros limeños.

---

## 📁 Estructura del Repositorio

```
Informe-Tecnico-Parque-Kennedy/
├── LICENSE
├── CITATION.cff
├── README.md
├── Informe/
│   ├── Informe.tex          # Fuente LaTeX principal
│   ├── jaes.cls             # Clase de documento JAES
│   ├── jaes.bib             # Bibliografía
│   ├── jaes.bst             # Estilo bibliográfico
│   ├── Informe.pdf          # PDF compilado (versión archivada en Zenodo)
│   ├── cuted.sty            # Paquete para columnas mixtas
│   └── orcidlink.sty        # Paquete para enlaces ORCID
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

## 🛠️ Cómo Compilar el Informe

**Requisitos:** LaTeX (TeX Live / MiKTeX) con `latexmk`, paquetes estándar + `jaes.cls` incluida.

```bash
cd Informe
latexmk -pdf Informe.tex
```

El PDF generado (`Informe.pdf`) es idéntico al archivado en Zenodo (DOI: 10.5281/zenodo.21695655).

---

## 📖 Metodología Resumida

1. **Muestreo**: Muestra compuesta, reducción por cuarteo normado (NTP 339.089)
2. **Humedad gravimétrica**: Secado a 105 °C hasta peso constante (NTP 339.127)
3. **Densidad aparente**: Método del cilindro volumétrico (ASTM D7263) sobre tierra fina
4. **pH**: Potenciometría en suspensión 1:2.5 (suelo:agua) según ISO 10390
5. **Conductividad eléctrica**: Suspensión suelo-agua 1:2.5 (NTP-ISO 11265) — **no** extracto de saturación
6. **Textura**: Tamizado mecánico seco con serie de 8 tamices (NTP 339.128) — **no** Bouyoucos/hidrómetro
7. **Materia orgánica**: Pérdida por ignición (LOI) a **505°C** — **no** 440°C

---

## 📄 Cómo Citar

Si usa este trabajo, cite como:

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

O use el archivo `CITATION.cff` para citación automática en GitHub/Zenodo.

---

## 📜 Licencias

| Componente | Licencia |
|------------|----------|
| Código / scripts / LaTeX source | [MIT](LICENSE) |
| Documento PDF archivado (Zenodo) | [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/) |

---

## 🔗 Enlaces Relacionados

- **Zenodo (versión archivada):** https://doi.org/10.5281/zenodo.21695655
- **GitHub Repositorio:** https://github.com/s7ex-j/Informe-Tecnico-Parque-Kennedy
- **ORCID Autor:** https://orcid.org/0009-0009-7897-3439