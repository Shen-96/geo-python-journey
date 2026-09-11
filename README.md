# GeoPython Journey

Hands-on exercises across the Python geospatial stack — from data wrangling to spatial ML, with NZ-focused case studies.

## Tech Stack

`Python` · `NumPy` · `Pandas` · `GeoPandas` · `Rasterio` · `Xarray` · `PyTorch` · `PostGIS` · `Docker`

## Learning Roadmap

| Phase | Module | Status |
|-------|--------|--------|
| 1 | Python Core & Data Wrangling (NumPy → Pandas) | 🔲 In progress |
| 2 | Spatial Analysis (GeoPandas · Shapely · PostGIS) | 🔲 Planned |
| 3 | Raster & Remote Sensing (Rasterio · Xarray · GDAL) | 🔲 Planned |
| 4 | Spatial AI (PyTorch · TorchGeo · Open3D · PDAL) | 🔲 Planned |
| 5 | MLOps & Cloud (FastAPI · AWS · MLflow · Argo) | 🔲 Planned |

## NZ Case Studies

All exercises use New Zealand geospatial contexts:
- South Island city distance matrix (Christchurch → Dunedin → Wellington)
- Simulated LINZ cadastral parcel data
- NIWA climate station time series
- Christchurch LiDAR point cloud segmentation (future)
- Sentinel-2 land cover classification over Canterbury (future)

## Project Structure

```text
geo-python-journey/
├── 01_python_basics/
├── 02_numpy/
├── 03_pandas/
├── 04_geopandas/
├── 05_raster/
├── 06_spatial_ai/
├── projects/          # Portfolio-ready work
└── src/               # Reusable helpers
```

## Setup

```bash
conda create -n geo_learning python=3.13 -y
conda activate geo_learning
conda install -y jupyterlab ipykernel
```