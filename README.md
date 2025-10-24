# PM2.5–EGFR Association Analysis

This repository contains reproducible analysis scripts accompanying the manuscript  
**“PM2.5 exposure is associated with EGFR somatic mutations in non-small cell lung cancer.”**

The notebooks reproduce all key analyses and figures described in the paper, using publicly available R and Python packages.  


---

## 1. File Description
`01-EGFR-PM25-association.ipynb`: Performs association analysis between ambient PM2.5 exposure and EGFR mutations across the DFCI-Profile cohort.

`02-EGFR-mutation-subtype.ipynb`: Examines subtype-specific EGFR mutations (L858R, del19, ins20, etc.) stratified by smoking history.

`03-fine-map-pm25-component.ipynb`: Implements Bayesian fine-mapping (susieR) to identify PM2.5 components most strongly associated with EGFR mutations.

`04-multi-ancestry-analysis.ipynb`: Conducts multi-ancestry modeling and mediation analyses to quantify ancestry-specific EGFR mutation prevalence and PM2.5 effects.

`05-simulation.ipynb`: Runs simulation experiments to test collider bias and evaluate causal models linking PM2.5 exposure, EGFR mutation, and lung cancer risk.
