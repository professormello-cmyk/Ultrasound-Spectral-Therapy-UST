# Ultrasound Spectral Therapy (UST)
**Toward a Safe and Selective Oncology Treatment**

---

## Overview
Ultrasound Spectral Therapy (UST) is a **nonthermal, spectrum-guided oncological treatment** designed to selectively ablate malignant tissue by exploiting intrinsic vibrational eigenmodes.
Instead of relying on nonspecific thermal or cavitation mechanisms, UST leverages **spectral resonance** to induce targeted modal collapse, achieving safe and precise tumor disintegration.

This repository contains:
- Raw and processed **simulation data** (HDF5 format with metadata).
- **Python and COMSOL** scripts for spectral analysis and tumor modeling.
- **Jupyter notebooks** with complete workflows.
- Documentation for reproducing all figures and results from the paper.

---

## Repository Structure
```
UST/
│── data/                # HDF5 datasets with metadata (place files here)
│── notebooks/           # Jupyter notebooks for analysis and visualization
│── scripts/             # Python scripts (pipeline, utilities)
│── simulations/         # COMSOL spectral simulation manifests (.mph, .txt)
│── figures/             # Scripts or outputs to reproduce manuscript figures
│── LICENSE
│── requirements.txt
│── CITATION.cff
│── README.md
│── .gitignore
```
---

## Installation
```bash
pip install -r requirements.txt
```

## Quickstart
Open the notebook:
```bash
jupyter notebook notebooks/UST_demo.ipynb
```
Or run the pipeline script:
```bash
python scripts/spectral_pipeline.py --input data/example.h5 --out figures/
```

---

## Data and Code Availability
All raw and processed data, simulation manifests, code, and full computational environments are publicly available at the project repository.
An archived, versioned snapshot is available at Zenodo: https://doi.org/10.5281/zenodo.16888335

Data is provided in **HDF5** format with complete metadata and version history.
All code (**Python, COMSOL**), simulation manifests, and Jupyter notebooks are included for open and independent replication.

---

## Citation
If you use this work, please cite:

**Mello, C., Medina da Cunha, F.**  
*Ultrasound Spectral Therapy (UST): Toward a Safe and Selective Oncology Treatment*.  
Zenodo. https://doi.org/10.5281/zenodo.16888335

---

## License
This project is released under the **MIT License** (see `LICENSE`).

---

## Contact
- Prof. Cesar Mello — cesar.mello@cosmophys.org  
- Dr. Fernando Medina da Cunha — Centro de Oncologia Campinas

