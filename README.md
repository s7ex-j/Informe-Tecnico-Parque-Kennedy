# Informe Técnico: Caracterización Fisicoquímica de Suelos Urbanos del Parque Kennedy

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21695655.svg)](https://doi.org/10.5281/zenodo.21695655)

**Autor:** Jharol André Vilca Ramos  
**ORCID:** [0009-0009-7897-3439](https://orcid.org/0009-0009-7897-3439)  
**Afiliación:** Universidad Privada del Norte, Facultad de Ingeniería Industrial, Lima, Perú  
**Fecha:** Junio 2026  
**Licencia (código):** MIT  
**Licencia (documento archivado en Zenodo):** CC-BY-4.0  
**DOI (Zenodo):** [10.5281/zenodo.21695655](https://doi.org/10.5281/zenodo.21695655)

---

## Resumen

Se realizó la caracterización fisicoquímica de una muestra compuesta de suelo procedente del Parque Kennedy (Miraflores, Lima, Perú), un entorno urbano sometido a intensa actividad biogénica asociada a una elevada población felina. El estudio comprendió etapas de muestreo, reducción de muestra mediante cuarteo normado, y determinación de humedad gravimétrica ($23.10\% \pm 0.39\%$), densidad aparente ($1.61 \pm 0.05~\text{g/cm}^3$ en base aire-seca; $\approx 1.58 \pm 0.05~\text{g/cm}^3$ estimado a base seca de horno), potencial de hidrógeno (pH $7.09 \pm 0.03$), temperatura de la sesión de pH ($22.73 \pm 0.12~^\circ\text{C}$), conductividad eléctrica ($1970 \pm 60~\mu\text{S/cm}$), textura (franco-arenosa, $\approx 73\%$ arena, $\approx 24\%$ finos) y materia orgánica por LOI ($3.94\%$).

La elevada conductividad eléctrica, anómala para un parque urbano estándar ($< 500~\mu\text{S/cm}$), es consistente con la acumulación de sales solubles derivadas de aportes biogénicos continuos; el pH neutro refleja la capacidad tampón calcárea característica de los suelos costeros de Lima; la temperatura medida permite interpretar la espontaneidad y la velocidad de los procesos de volatilización y mineralización; la densidad aparente evidencia una compactación moderada asociada al uso recreativo intensivo; y el contenido de materia orgánica, en el extremo superior del rango regional reportado en estudios previos, es consistente con el aporte continuo de excretas felinas.

La información generada constituye una base fisicoquímica integral para interpretar los procesos de transformación en ecosistemas urbanos sometidos a aportes continuos de compuestos nitrogenados.

**Palabras clave:** Suelo urbano, Caracterización fisicoquímica, Salinización edáfica, Parque Kennedy

---

## Estructura del repositorio

```
github/
├── LICENSE
├── CITATION.cff
├── README.md
├── Informe/
│   ├── Informe.tex
│   ├── jaes.cls
│   ├── jaes.bib
│   ├── jaes.bst
│   ├── Informe.pdf
│   ├── cuted.sty
│   └── orcidlink.sty
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

## Cómo compilar el informe

Requiere LaTeX con los paquetes estándar y la clase `jaes.cls` incluida en `Informe/`.

```bash
cd Informe
latexmk -pdf Informe.tex
```

---

## Cómo citar

Si usa este trabajo, cite como:

```bibtex
@article{VilcaRamos2026,
  author  = {Vilca Ramos, Jharol André},
  title   = {Informe Técnico: Caracterización Fisicoquímica de Suelos Urbanos del Parque Kennedy},
  journal = {Informe Técnico},
  year    = {2026},
  month   = {6},
  doi     = {10.5281/zenodo.21695655},
  url     = {https://github.com/s7ex-j/Informe-Tecnico-Parque-Kennedy}
}
```

O use el archivo `CITATION.cff` para citación automática en GitHub/Zenodo.