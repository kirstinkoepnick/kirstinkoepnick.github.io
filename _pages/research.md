---
permalink: /research/
title: "Research"
author_profile: true
---

---

My research focuses on **climate dynamics and variability** across the atmosphere, ocean, and cryosphere. I use a combination of theory, numerical modeling, climate model analysis, and simple dynamical models to understand how ice sheets, sea ice, and large-scale modes such as ENSO and the QBO interact with eachother and the broader climate system.

A common thread in my work is the use of **model hierarchies**: pairing complex climate model output with idealized and conceptual models to isolate mechanisms, test hypotheses, and distinguish signal from noise in a highly variable climate system.

---

## 1. Paleoclimate Modeling: understanding glacial cycles

One line of my research examines the **growth and retreat of icesheets** (in particular the Laurentide Ice Sheet (LIS)) across the glacial cycles.

<figure style="float:right; width:40%; max-width:300px; margin:0 0 0.5rem 2rem; text-align:center;">

  <img src="/images/smb_schematic.png" alt="Glacier mass balance schematic" style="width:100%; height:auto;">

  <figcaption style="font-size:0.75em; color:#666; margin-top:0.25rem;">
    Glacier mass balance and atmospheric circulation. By NASA. From Wikimedia Commons.
  </figcaption>

</figure>

- Generally, I examine how the **surface mass balance (SMB)** of various ice sheets responds to changes in albedo, temperature, precipitation, and sea ice cover.
- I compute the SMB of the LIS using the isotope-enabled iTRACE simulation and compare it with mass-loss rates inferred from geophysical reconstructions (e.g., ICE-6G).
- Ongoing work investigates **why the LIS grew near 80 ka but retreated rapidly near 12 ka**, disentangling the relative roles of insolation, sea-ice extent, circulation changes, and feedbacks tied to albedo and meltwater.

Together, these projects aim to clarify the conditions under which ice-sheet evolution is primarily controlled by external forcing versus internal climate variability.

---

## 2. Pacific Teleconnections: ENSO–QBO interactions and large-Scale variability

Another focus of my work is the interaction between **ENSO (El Niño–Southern Oscillation)** and the **Quasi-Biennial Oscillation (QBO)**.

<figure style="float:left; width:40%; max-width:300px; margin:0 1.5rem 0.5rem 0.5rem; text-align:center;">

  <img src="/images/ENSO_schematic_large.png" alt="ENSO schematic" style="width:100%; height:auto;">

  <figcaption style="font-size:0.75em; color:#666; margin-top:0.25rem;">
    ENSO schematic. NOAA Climate.gov, based on original provided by Eric Guilyardi.
  </figcaption>

</figure>

- Using **reanalysis and CMIP6 preindustrial control runs**, I evaluate whether the observed ENSO–QBO correlation is evidence of a robust dynamical coupling or can be explained by statistical coincidence in a short record.
- In companion work, I develop **simple dynamical models** to test candidate mechanisms, including QBO impacts on wave propagation, tropical upwelling, and ENSO amplitude and timing.
- Separately, I advise an undergraduate research student working on machine learning techniques to classifying westerly wind bursts.

This combination of data analysis and theory aims to determine when we can confidently claim a mechanistic teleconnection versus when apparent relationships are consistent with stochastic variability.

---

## 3. Sea Ice, Surface Mass Balance, and High-Latitude Feedbacks

I am also interested in how **sea-ice variability** interacts with ice-sheet and ice-sheet–adjacent climates.

<figure style="float:right; width:40%; max-width:300px; margin:0 0 0.5rem 2rem; text-align:center;">

  <img src="/images/seaice_smb_schematic.jpeg" alt="sea ice smb schematic" style="width:100%; height:auto;">

  <figcaption style="font-size:0.75em; color:#666; margin-top:0.25rem;">
    How seaice variability might affect SMB (of GrIS). Created by Kirstin Koepnick.
  </figcaption>

</figure>

- I study how changes in **Arctic sea ice** affect the **surface mass balance of the Greenland and Laurentide Ice Sheets**, focusing on the competing roles of insulating sea ice, open-ocean heat fluxes, and atmospheric circulation.
- Using idealized experiments and simple energy-balance and diffusion models, I investigate how **sea-ice–driven anomalies** in surface fluxes and temperature propagate into the snow and firn and influence melt and refreezing.

These projects connect high-latitude processes to longer-term evolution of ice sheets and help clarify the physical pathways through which sea ice can modulate SMB.

---

## Methods and Model Hierarchies

Across these projects, I use:

- **Climate model simulations**: for my paleoclimate research, I run CESM2 with CAM5 physics adjusting topography and bathymetry for LGM and 12ka conditions
- **Climate model analysis:** CESM2, iTraCE, CMIP6 control runs  
- **Simple and intermediate-complexity models:** conceptual climate and ice-sheet models, stochastic ENSO models  
- **Numerical modeling:** diffusion and energy-balance models for subsurface temperature and SMB  
- **Statistical tools:** bootstrapping, surrogate time series, and machine-learning-based classification of westerly wind bursts  

By moving up and down a hierarchy of models and data sources, I aim to bridge mechanistic understanding with realistic climate behavior.
