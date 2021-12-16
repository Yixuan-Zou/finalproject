### <center>*Final Project Proposal*</center>

##### <center>***Yixuan Zou, yz3909***</center>
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/pangeo-data/pangeo-docker-images/2021.09.30?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252FYixuan-Zou%252Ffinalproject%26urlpath%3Dtree%252Ffinalproject%252F%26branch%3Dmaster)
##### Hypothesis: 
By combining the wind resource in multiple locations will generate more stable power.

This project aims to analysis the effect of combining the diversity of wind time series across different wind resource regions and to answer the question whether more stable power can be produced when we connect regions. Analysis will be done using one year hourly capacity factor data of eight sites (shown in the Fig1), which indicates the wind potential. New York State hourly solar potential data and hourly electricity load data in 2011 will be used to analyse the possibility of fulfilling electricity load with renewable energy (wind and solar).

<strong><em> Data are provided by Quadracci Sustainable Engineering Lab in Columbia University.</strong></em>

##### Dataset: [wind_po_hr.csv ](https://zenodo.org/record/5739406#.YabNWNCZPZs)
<em>Data is selected from the integrated model data developed by NREL for 126000 potential wind sites.</em>
<p>Provenance 1: Draxl C, Clifton A, Hodge BM, McCaa J. The Wind Integration National Dataset (WIND) Toolkit. Appl Energy 2015;151:355–66. https://doi.org/10.1016/j.apenergy.2015.03.121.</p>
<p>Provenance 2: Draxl C, Hodge B-M, Clifton A, McCaa J. Overview and Meteorological Validation of the Wind Integration National Dataset Toolkit. 2015</p>

##### Dataset: [solar_potential ](https://zenodo.org/record/5750726#.YalDatCZPZs)
<em>Data is grid-scale solar PV sites in NREL model solar dataset, aggregated by region in NYS.</em>
<p>Provenance 1: Hummon M, Ibanez E, Brinkman G, Lew D. Sub-Hour Solar Data for Power System Modeling From Static Spatial Variability Analysis. 2nd Int. Work. Integr. Sol. Power Power Syst., 2012</p>
<p>Provenance 2: Blair N, Dobos AP, Freeman J, Neises T, Wagner M, Ferguson T, et al. System Advisor Model, 2014.1.14: General Description. NREL Rep No TP-6A20-61019, Natl Renew Energy Lab Golden, CO 2014</p>

##### Dataset: [electricity_load](https://zenodo.org/record/5750734#.YalDsdCZPZs)
<em>Data is from NYISO and is aggregated into single time series for NYS in 2011.</em>
<p>Provenance: New York Independent System Operator (NYISO). Market and Operational Data 2020. https://www.nyiso.com/energy-market-operational-data. </p>

![wind_image](windresource.jpg)

<ol>
<li> NY1 (NY_1 onshore; column B in csv file)</li>
<li> NY2 (NY_2 onshore; column C in csv file)</li>
<li> New England (NEWE onshore; column D in csv file)</li>
<li> Midwest (MW onshore; column E in csv file)</li>
<li> OSW1 (NEWE offshore; column F in csv file)</li>
<li> OSW2 (NY offshore; column G in csv file)</li>
<li> OSW3 (RFCE offshore; column H in csv file)</li>
<li> OSW4 (SRVC offshore; column I in csv file)</li>
</ol>

##### Plan to do
- Investigate the seasonal wind energy trend in 8 sites and combination 
- Investigate the diurnal energy trend in 8 sites and combination
- Investigate whether the renewable energy availability (solar and wind) in upper New York state can meet the requirement of local electricity load, if not, what is the energy gap between generation and load