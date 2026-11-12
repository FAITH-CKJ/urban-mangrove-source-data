# Source data for global urban mangrove trajectories

This repository provides the source data accompanying **Hybrid spatiotemporal representation learning for reconstructing global urban mangrove change trajectories during 2000–2025**, by Kangjie Cao, Mingming Jia and Ruili Li.

[Download Source_Data.zip](https://github.com/FAITH-CKJ/urban-mangrove-source-data/raw/refs/heads/main/Source_Data.zip)

The archive contains numerical tables, selected spatial arrays and observation metadata supporting the figures, tables and methods in the manuscript and Supplementary material.

| Format | Files | Contents |
|---|---:|---|
| CSV | 102 | Numerical tables, classification and change statistics, habitat histories, spatial summaries and the file index |
| JSON | 15 | Class definitions, spatial grids, observation sources, method parameters and software versions |
| NPZ | 19 | Spatial arrays, reference labels, model outputs and observations for the displayed examples |
| GeoTIFF | 26 | Reference-composite spatial support masks |
| TXT | 1 | Reading instructions |

After extraction, start with `README.txt`, `CONTENTS.csv` and `metadata.json`. The index describes each data file and records its size and SHA-256 checksum. CSV files use UTF-8 and a header row. NumPy archives can be opened with `numpy.load(path, allow_pickle=False)`.

The study reconstructs annual land cover during 2000–2025 within a fixed urban-associated coastal domain on a 30 m EPSG:6933 grid. Each mapped pixel represents 0.0009 km². The six covers are mangrove, tidal flat, other vegetation, water, built-up land and other non-water land. Unknown observations and outside-domain NoData retain their separate codes. Shared metadata define the class codes, units and denominators used by each data product.

**Archive size:** 15,425,312 bytes.  
**Archive SHA-256:** `3ba046eaf6afd1024a07f83febc85ba2412621b3c61fb8ac9e4651cad4979247`.
