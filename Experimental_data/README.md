The experimental datasets are provided separately for the cycloheximide (CHX) chase and NanoBRET ubiquitination assays.

## CHX chase assays

Directory `CHX_chase_assays` contains subdirectory for each studied protein, HiBiT-VHL or HiBiT-SOCS1, with the following architecture:

```
.
├── Experiment_#
│   ├── Half-life_luminescence.xlsx - raw luminescence measurements from the CHX chase assay combined with the HiBiT Lytic Detection Assay
│   ├── Plate_description.xlsx - description of conditions applied in each plate's well
│   └── Viability_fluorescence.xlsx - raw fluorescence measurements from the CellTiter-Fluor Cell Viability Assay
```

## NanoBRET ubiquitination assays

Directory `NanoBRET_assays` directory contains subdirectory for each studied protein, VHL or SOCS1 (for both N-/C-terminal locations of the NanoLuc tag), denoted as  NanoBret-VHL and NanoBret-SOCS1, respectively, with the following architecture:

```
.
├── Experiment_#
│   ├── NanoBret.xlsx  - raw donor and acceptor light emission measurements from the NanoBRET Nano-Glo Detection Systems (Standard) Assay
│   ├── Plate_description.xlsx - description of conditions applied in each plate's well
│   └── Viability_luminescence.xlsx - raw luminescence measurements from the CellTiter-Glo 2.0 Cell Viability Assay
```
