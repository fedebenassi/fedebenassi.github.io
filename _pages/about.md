---
permalink: /
title: " "
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a PhD student in *Future Earth, Climate Change and Societal Challenges* at the University of Bologna and the Euro-Mediterranean Center on Climate Change (CMCC). With a background in physics, I use machine learning and observations to study ocean processes across different spatial and temporal scales.

[Download my CV (PDF)]({{ '/files/FedericaBenassi_CV_Nov2026.pdf' | relative_url }})

## Projects

### WaveGraph: an autoregressively stable wave model emulator 🌊

WaveGraph is a graph neural network designed to reproduce wave model output on an unstructured grid defined over the entire Mediterranean Sea. It remains stable over long simulations without reinitialization, allowing to reconstruct 17 years of wave conditions at three-hour intervals without blowing up. We compared the results with buoy observations and satellite altimetry, and WaveGraph achieved the same error as the reference simulation, at a *very small fraction of computational cost*! Tests also showed that wind helps keep the model stable, while information about previous waves improves its accuracy. Applications to other basins and high-resolution downscaling are ongoing. [Read the preprint](https://doi.org/10.48550/arXiv.2608.16449).

### Ocean filaments and carbon transport 🦠

In coastal upwelling regions, currents bring nutrient-rich water to the surface, supporting phytoplankton growth. I developed a clustering approach to identify offshore filaments from satellite observations of temperature and chlorophyll anomalies in six upwelling systems. I then designed a physics-based method to estimate offshore transport of carbon away from the coast, and how much these filaments contribute (< 5%). [Read the publication](https://doi.org/10.1029/2026gl122097).

### Air–sea CO₂ exchange 

The ocean exchanges carbon dioxide with the atmosphere, but estimating the rate of that exchange from observations remains challenging. In this ongoing project, I developed a neural network that learns a correction to an established physical approach using in situ observations collected from cruises, as well as the uncertainty associated to each prediction. 

## Experience

- **Aug-Dec 2025**: Visiting student at [Coastal Biogeochemistry Dynamics Lab](https://samanthasiedlecki.wixsite.com/coastalbiogeodynlab), University of Connecticut (Groton, 🇺🇸). I worked on estimates of air–sea CO₂ exchange using observational data.
- **Apr-Jun 2023**: Visiting student at [Phytooptics Lab](https://www.awi.de/en/science/climate-sciences/physical-oceanography/main-research-focus/ocean-optics.html), Alfred-Wegener Institute (Bremerhaven, 🇩🇪). I worked with satellite observations on the research that became the ocean filaments project.

## Education

- **2023-present**: PhD in Future Earth, Climate Change and Societal Challenges (University of Bologna and CMCC)
- **2021-2023**: Master's degree in Physics of the Earth System (University of Bologna). Awarded the Department of Physics and Astronomy's prize for the best master's thesis.
- **2017-2020**: Bachelor's degree in Physics (University of Modena and Reggio Emilia)

## Publications

- Benassi, F., Mentaschi, L., Causio, S., Holmberg, D., Federico, I., & Pinardi, N. (2026). Decadal wave reconstruction in the Mediterranean Sea with graph neural networks. Submitted to *Artificial Intelligence for the Earth Systems*. [Preprint available](https://doi.org/10.48550/arXiv.2608.16449).

- Benassi, F., Siedlecki, S., Pinardi, N., Mentaschi, L., Cessi, P., Bianconcini, S., & Federico, I. (2026). A Satellite‐Based Estimate of the Contribution of Filamentary Structures to Lateral Carbon Transport in the Pacific and Atlantic Upwelling Systems. Geophysical Research Letters, 53(18). <https://doi.org/10.1029/2026gl122097>

## My most recent talks

| --- | --- | --- | --- |
| 2026 | Predicting wave parameters on unstructured grids using a Graph Neural Network | OSM 2026 | 🏴󠁧󠁢󠁳󠁣󠁴󠁿 |
| 2025 | A satellite-based estimate of the contribution of filamentary structures to lateral carbon transport in the Pacific and Atlantic Upwelling systems | AGU 2025 |🇺🇸 |


## Teaching

| --- | --- | --- | 
| 2025 | Lecturer for COMPASS-Philippines spring school | 🇵🇭|
| 2023 | Python crash course for Science of Climate students | 🇮🇹 |
