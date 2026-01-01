# GVS-on-H-reflex
In our study, we investigated how galvanic vestibular stimulation (GVS) influences neuromuscular responses, specifically focusing on the H-reflex and M-wave in the soleus muscles. 
Analysis code and (optionally) data supporting:  
**Effects of Galvanic Vestibular Stimulation (GVS) on H-Reflex and M-Wave Responses in Bilateral Soleus** (Medium, May 13, 2025).

## What this repo contains
- `src/` – analysis scripts (cleaning, summaries, plots, Hmax/Mmax ratio)
- `data/raw/` – raw dataset (add only if shareable)
- `data/processed/` – cleaned/derived datasets
- `outputs/figures/` – generated figures
- `outputs/tables/` – generated summary tables
- `docs/` – documentation assets

## Reproduce the analysis (R)
Run scripts in order:
1. `src/01_import_clean.R`
2. `src/02_summary_stats.R`
3. `src/03_plots.R`
4. `src/04_hmax_mmax_ratio.R`

## Data notes
If human-subject data cannot be shared publicly, keep `data/raw/` empty and document access requirements in `data/README.md`.

## Reference
Medium post: https://medium.com/@vijaymuthaiah/effects-of-galvanic-vestibular-stimulation-on-h-reflex-and-m-wave-responses-in-bilateral-soleus-3b720cddef28

