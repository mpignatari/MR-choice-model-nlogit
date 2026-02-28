# Coastal conservation & blue carbon (Oregon) — DCE dataset + NLOGIT code

This repository provides NLOGIT/LIMDEP code to reproduce discrete choice model estimation for the Oregon nearshore management / blue-carbon stated-preference study.

## Data
The dataset is publicly available via USU DigitalCommons:
- Landing page: https://digitalcommons.usu.edu/all_datasets/260/
- DOI: https://doi.org/10.26078/VJP2-WH98

License: CC BY 4.0 (see the DigitalCommons record).

## Code
- `code/MR_NLOGIT_codes.lim` — NLOGIT/LIMDEP script for model estimation.

## How to reproduce
1. Download the dataset package from the DigitalCommons page (includes `.csv` and `.lim`).
2. Place the downloaded `.csv` in a local `data/` folder (not tracked by git).
3. Open NLOGIT/LIMDEP and set the working directory to this repository.
4. Run: `code/MR_NLOGIT_codes.lim`

## Citation
Caplan, A. (2026). *Coastal conservation and blue carbon: Willingness to pay for changes to nearshore management in Oregon* [Data set]. Utah State University. https://doi.org/10.26078/VJP2-WH98
