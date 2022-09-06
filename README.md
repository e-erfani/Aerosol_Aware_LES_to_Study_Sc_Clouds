# Aerosol impacts on stratocumulus-to-cumulus transition using LES

### Descriptions:
This project is a numerical modeling work at UW to study aerosol-cloud interaction (ACI) over Northeast Pacific. The Large Eddy Simulation (LES) experiments are conducted using SAM-UW model. Only the post-processing of modeling outputs is documented here. If you are interested in reproducing the model outputs, check out the relevant Zenodo repository:
https://doi.org/10.5281/zenodo.7005166

### Author:
- Ehsan Erfani

### Codes:
- output_RF06_Tr2p3_multi_cases_NEW_Github.ipynb: Use LES SAM UW model outputs and observations and perform post-processing analysis such as time series and time-height plots for the L06 case.
- output_RF10Tr2p3_multi_cases_NEW_Github.ipynb: Same as above, but for L10 case.
- Indirect_effects_obs_NEW_Github.ipynb: Use all LES runs and observations and provide numerous results such as time-averaged plots, transition analysis, decomposition to various effects, PDF calculations, maps, and cross-sections.

### Inputs:
- SAM-UW output files in NetCDF format.
- SAM-UW forcing files in NetCDF format.
- Observational and reanalysis data files in NetCDF format.

### Requirements:
- Python3 in Jupyter Notebook (installed by Anaconda).
- See the beginning of each code for the required Python3 libraries.

### The analyses are featured in:
Erfani E., P. Blossey, R. Wood, J. Mohrmann, S. Doherty, M. Wyant, K. O, 2022: Simulating aerosol lifecycle impacts on the subtropical stratocumulus-to-cumulus transition using large-eddy simulations, J. Geophys. Res. Atmos. https://doi.org/10.1002/essoar.10511558.1
