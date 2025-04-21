# The synoptic_tools Repository
This repository includes Python scripts I've written for my PhD work in synoptic meteorology. There are currently two Python notebooks available:
1. `omega_inversion.ipynb` allows users to solve for the quasi-geostrophic vertical motion due to different adiabatic processes in the atmosphere. A sample netCDF file containing ERA5 data that this Jupyter notebook is set up to work with is available in `./data_omega_inversion/`.
2. `relative_composites.ipynb` demonstrates how to construct to spatial composites using data at different times within domains that are drawn relative to a series of central points. A sample netCDF file containing ERA5 data that this Jupyter notebook is set up to work with is available in `./data_relative_composites/`.
3. `sawyer_eliassen.ipynb` allows users to solve for the secondary circulation occurring transverse to a frontal zone or jet streak along a vertical cross-section through the frontal zone/jet streak using the Sawyer-Eliassen equation. A sample netCDF file containing ERA5 data that this Jupyter notebook is set up to work with is available in `./data_sawyer_eliassen/`.

# Cloning the Repository
To clone this repository, insert the following command into your terminal:
```sh
git clone https://github.com/careiher/synoptic_tools.git
```
Images appearing in the Jupyter notebooks (stored in `./images`) will likely not render properly unless the entire repository is cloned.

