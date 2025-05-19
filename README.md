# rebound-passenger-aviation

This repository contains supporting files for my master thesis titled _Exploring the Rebound in Passenger Aviation._  The research examines the structure and underlying dynamics of the passenger aviation system while estimating the potential magnitude of the rebound effect to effectively assess its impact. Given market-specific uncertainties and the lack of transparent data, this research combines a System Dynamics (SD) modeling approach with scenario analysis to examine how these uncertainties influence the magnitude and potential impact of the rebound effect. The files are structured as follows:

**scenario_analysis**
This directory contains all code files used for the scenario analysis, as well as the single model runs for the reference scenario, which provide context for the plotted scenario outcomes:

- **baseline_scenario.ipynb** - single baseline simulation
- **reference_scenario.ipynb** - single rebound simulation for reference scenario
- **results_and_PRIM.ipynb** - plots of the scenario outcomes and PRIM analysis
- **results_with_flightrestriction.ipynb** - plots of scenario outcomes under a flight restriction
- **run_experiments_with_flightrestriction.ipynb** - 1000 rebound simulation runs under a flight restriction
- **run_experiments_without_flightrestriction.ipynb** - 1000 rebound simulation runs 

**Data sources and estimations.xlsx** - contains Excel file supporting the data used in the SD model

**MODEL FINAL.mdl** - the SD model developed for this research in Vensim DSS 10.2.2
