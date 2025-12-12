# Colorado Invertebrate Single Taxon Multi-Stressor Modeling
### Time-varying matrix population models for Colorado River macroinvertebrates under multiple stressors
This repository contains all data, scripts, and outputs associated with the manuscript: *Forecasting the effects of multiple stressors on aquatic invertebrates in the Grand Canyon-Colorado River ecosystem* (working title).

Freshwater ecosystems are increasingly shaped by multiple interacting stressors, including climate-driven warming, hydropower-driven daily flow fluctuations (load-following or hydropeaking), and high-flow releases. To understand how these environmental stressors interact to influence aquatic macroinvertebrates, we developed five time-varying, stage-structured matrix population models for macroinvertebrate taxa in the Colorado River downstream of Glen Canyon Dam.
Using these models, we simulated eight combinations of stressors (temperature regime, hydropeaking, high-flow events), projected standing biomass, and quantified taxon-specific responses. We found that temperature regime had a significant impact on all populations, multi-stressor interactions often produced nonlinear responses, the effect and response to those eight different simulations was taxon-dependent. 

## Repository Structure
```
ColoradoInvertSingleTaxon/
│
├── data/ # all data used or produced in the modeling 
│   
│
├── scripts/ # all scripts that can be run in R
│   └── HPC/  # all scripts that were run on the Oregon State University NOVUS HPC  
│
├── results/ 
│   └── FigGen2.R # R script to produce figures in the manuscript
│
└── README.md   # This file
```

## Reproducibility Instructions

1. Clone the repository
```
git clone https://github.com/Angelika-Kurthen/ColoradoInvertSingleTaxon.git
cd ColoradoInvertSingleTaxon
```
2. Install required R packages
A complete list is found at the top of each script.

3. Run ```FigGen2.R```, which sources all other scripts and data

For questions about the modeling workflow, data, or manuscript, please contact:

Angelika Kurthen

Email: kurthena@oregonstate.edu
