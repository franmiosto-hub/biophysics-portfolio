# Computational Biophysics — Scripting & Analysis Portfolio

Working research scripts, consolidated into **5 project notebooks** covering **19 analyses** across protein–RNA interactions, molecular dynamics, binding thermodynamics, and quantitative data analysis. Originally Google Colab notebooks; organised by project, cleaned for readability, de-identified, and pruned of unused or broken scripts — original methods preserved.

> 🔬 **Live page:** open `index.html`, or enable GitHub Pages (see `SETUP_GITHUB.md`).

## Projects

| # | Project | Analyses | Highlights |
|---|---|---|---|
| 01 | [Peptide microarray analysis of protein–RNA binding](./01_peptide_microarray_binding_analysis.ipynb) | 6 | End-to-end pipeline from raw GenePix scans to per-residue RNA-binding contribution scales via non-negative least squares. |
| 02 | [Binding thermodynamics & curve modelling](./02_binding_thermodynamics_and_curves.ipynb) | 4 | Fraction-bound simulations, theoretical NMR titration curves, and ΔG→Kd conversion from published values. |
| 03 | [Molecular dynamics & free-energy analysis](./03_molecular_dynamics_analysis.ipynb) | 5 | GROMACS post-processing: time-series observables, protein–RNA contact maps, free-energy matrices, BAR convergence, and EDS alchemical topologies. |
| 04 | [Sequence, structure & data-visualisation utilities](./04_sequence_structure_utilities.ipynb) | 3 | Assorted smaller analyses: IUPred2 disorder profiles, amino-acid van der Waals volumes, and annotated heatmaps of tabular NMR data. |
| 05 | [PhD-student wellbeing survey analysis](./05_phd_survey_wellbeing_analysis.ipynb) | 1 | A standalone statistics project: scoring PHQ-9 / GAD-7 questionnaires and comparing groups. (Survey data intentionally excluded.) |

## Repository layout
```
portfolio/
├── 01_peptide_microarray_binding_analysis.ipynb
├── 02_binding_thermodynamics_and_curves.ipynb
├── 03_molecular_dynamics_analysis.ipynb
├── 04_sequence_structure_utilities.ipynb
├── 05_phd_survey_wellbeing_analysis.ipynb
├── data/topology_files/   # example GROMACS/EDS .itp inputs
├── index.html             # themed landing page
├── README.md
├── requirements.txt
└── SETUP_GITHUB.md
```

## Tech stack

`Python` · `NumPy` · `pandas` · `SciPy` · `matplotlib` · `seaborn` · `Biopython` · `SMArt` · GROMACS (`.xvg`, `.itp`) · GenePix microarray exports (`.gal`)

## Data & reproducibility

- Raw and unpublished data files are **intentionally excluded**; notebooks reference generic relative filenames.

## About

**Fran Miočić-Stošić** · [email](mailto:fran.mio.sto@gmail.com) · [GitHub](https://github.com/franmiosto-hub) · [ORCID](https://orcid.org/0009-0005-8384-3074)

_Replace the placeholders above (and in `index.html`) before publishing._

