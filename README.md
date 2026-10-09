# Pancreas morphology across the lifespan in type 1 diabetes

Statistical code and morphometric measurements accompanying:

> Kusmartseva I, Verney E, Meier A, et al. *Pancreas morphology across the
> lifespan in type 1 diabetes.* Diabetologia.

## Contents
- `Pancreas_Morphology_Diabetologia_2026.ipynb` — Jupyter notebook (mixed **SAS** and **R** cells via `%%SAS`
  / `%%R` magics) that assembles the analysis dataset and reproduces the
  statistics, figures, and supplementary tables.
- `panc_morphometric_measurement_data.xlsx` — case IDs + the five pancreas
  morphometric measurements collected for this study.

## Data you must obtain separately (not redistributed here)
Donor clinical, demographic, HLA, and genetic (GRS2) variables are controlled by
the Network for Pancreatic Organ Donors with Diabetes (nPOD). Obtain them as a
qualified investigator at https://portal.jdrfnpod.org:
- nPOD **All-Download** export
- nPOD **Genetic-Download** export

See the README cell at the top of the notebook for the full setup, including the
required Excel "re-save" of the nPOD files and the Windows-specific notes.

## Requirements
SAS (via SASPy) and R, with R packages: rms, rio, dplyr, tidyr, ggplot2,
cowplot, car, extrafont. Developed on **Windows**.

## Contact
jkaddis@coh.org
