# Energy Conservation in Supernova SN2023ixf

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jsuarez314/econservation_sn2023ixf/HEAD)

## Overview
This repository contains a Jupyter Notebook that explores the principles of **energy conservation applied to Supernova SN2023ixf**. Using observational estimates and simplified models, we calculate and compare the primary energy components released during the explosion:

- **Kinetic energy**
- **Radiant energy**
- **Thermal energy**

The objective is to evaluate how these contributions relate to the total explosion energy and to discuss discrepancies between **theoretical expectations** and **observationally derived values**.

This exercise highlights both:

- The enormous energetic processes involved in a supernova explosion.
- The role of energy conservation as a fundamental tool for understanding extreme astrophysical phenomena.

The analysis is based on observational data from the article:

> *“Multiband Simultaneous Photometry of Type II SN 2023ixf with Mephisto and the Twin 50-cm Telescopes.”*

---

## Repository Contents

- **`SN2023ixf_energy_analysis.ipynb`** – Jupyter Notebook with the full analysis and discussion.
- **`SN2023ixf_data.txt`** – Data file containing photometric and physical parameters.

---

## Data Description

The data file provides the following columns:

- **MJD/day** – Modified Julian Date (observation time)
- **log[L/ergs−1]** – Logarithm of the luminosity in ergs per second
- **log[Teff/K]** – Logarithm of the effective temperature in Kelvin
- **log[Rph/cm]** – Logarithm of the photospheric radius in centimeters

These values are used to estimate the energy components of the supernova.
