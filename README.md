# Climate Projections for the Czech Republic – CMIP6 Analysis

Analyzed historical and future climate projections for the Czech Republic using the GFDL-ESM4 model from CMIP6. The project covers temperature and precipitation changes under three emission scenarios (SSP1-2.6, SSP3-7.0, SSP5-8.5) from 1850 to 2100.

## What I did

- Processed NetCDF climate data and extracted time series for temperature and precipitation
- Compared three SSP scenarios to see how different emission pathways affect Czechia's climate
- Applied spatial downscaling (bilinear interpolation and kriging) to increase model resolution from 55 km to 14 km
- Created animated precipitation maps showing changes over time
- Identified when key warming thresholds (1.5°C, 2.0°C) are reached under each scenario
- Ran the full workflow on Metacentrum HPC infrastructure using Singularity containers

## Key findings

- Czechia is projected to warm by 1.2–3.7°C by 2100 depending on the emission scenario
- Northern regions generally become wetter while southern areas may experience drying
- Under SSP5-8.5, the 1.5°C and 2.0°C thresholds are reached around 2055 and 2065

## Tools

R (terra, sf, ncdf4, tidyverse, gstat, ggplot2, gganimate, zoo, viridis), Quarto, Singularity containers, Metacentrum HPC

## Course

Big Data Analysis and Cloud Computing in R – B.Sc. Environmental Data Science, Czech University of Life Sciences Prague (2nd year)
