# Multi-model Intercomparison Project on the Saskatchewan-Nelson-Churchill River Basin (Nelson-MiP) 
**Funded under IMPC project of Global Water Futures program.**
<p align="center">
   <img src="img/logos/IMPC_Horizontal_FC.png" width="30%" height="8%" hspace="0.5%" />
   <img src="img/logos/gwf_globe.png" width="9.5%" height="10%"  />
</p>

This page/directory contains the documentation of the Multi-model Intercomparison Project on the Saskatchewan-Nelson-Churchill River Basin (Nelson-MiP), funded under IMPC project of Global Water Futures program.

<!--ts-->
# Table of content
   * [Objectives](#objectives)
   * [Candidate models and modellers](#Candidate-models-and-modellers)
   * [Contributers](#Contributers)
   * [Project phases](#project-phases-tentative)
   * [Deliverables](#deliverables)
   * [Reporting](#reporting)
   * [Design of the modeling experiments](#design-of-the-modeling-experiments)
      * [Input data](#input-data)
          	
		* [DEM](#dem-and-derived-products)
	  	* [Land use/land cover](#land-useland-cover)
	  	* [Soil data](#soil-data)
	  	* [Water table depth](#water-table-depth)
	  	* [Meteorological/ Climate forcing data](#meteorological-climate-forcing-data)
	  	* [Remote sensing data](#remote-sensing-data-for-model-validation)
	  	* [Hydrometric data](#hydrometric-data)
      
      * [Model calibration and validation](#model-calibration-and-validation)
	  	
		* [Metrics for model calibration and validation](#metrics-for-model-calibration-and-validation)
   
   * [Nelson-MiP survey](#Nelson-MiP-survey)
   * [19 CMIP5 bias-corrected GCMs for Phase 3](#19-CMIP5-bias-corrected-GCMs-for-Phase-3)
   * [Mailing list](#Mailing-list)
<!--te-->
   
# Objectives 
The objectives of this research project led by the University of Calgary-Hydrologic Analysis Lab (UC-HAL) on a sub-watershed of the Saskatchewan-Nelson-Churchill river basin are to: 
1. compare participating hydrologic and land surface models with respect to their performance in reproducing long-term runoff and various hydrologic signatures; 
2. understand the drivers of the differences among models from an internal process perspective; 
3. assess the realism of different algorithms in simulating the same processes; 
4. assess the reliability of the models for the prediction of key hydrologic processes and streamflow under changing climate conditions. 
5. develop robust ensemble averaging methods to reduce the range of uncertainties in streamflow projection under changing climate conditions.

# Candidate models and modellers

| Model | Watersheds/Scale | Institutions | Contact persons |
| :---: | :---: |  :---: | :---: |
|HYPE  |	Nelson Churchill  |	UC-HAL |	<a href="mailto:tricia.stadnyk@ucalgary.ca">Tricia Stadnyk </a><br> <a href="mailto:mohamedismaiel.ahmed@ucalgary.ca">Mohamed Ismaiel Ahmed </a><br> <a href="mailto:oyemonbade.awoye@ucalgary.ca">Hervé Awoye </a><br> <a href="mailto:ajay.bajracharya@ucalgary.ca">Ajay Bajracharya </a><br>|
|SWAT-GIW  |	Upper Assiniboine  |	Water Security Agency |	<a href="mailto:Ameer.Muhammad@wsask.ca">Ameer Muhammad </a><br> <a href="mailto:curtis.hallborg@wsask.ca">Curtis Hallborg </a><br>|
|SWAT-RRB  |	Red River Basin  |	University of Manitoba |	<a href="mailto:Masoud.Asadzadeh@umanitoba.ca">Masoud Asadzadeh </a><br> <a href="mailto:huangy32@myumanitoba.ca">Yinlong Huang </a><br>|
|SWAT-GWF  |	Nelson  |	University of Alberta |	<a href="mailto:faramarz@ualberta.ca">Monireh Faramarzi </a><br> <a href="mailto:khalili@ualberta.ca">Pouya Khalili </a><br> <a href="mailto:masud@ualberta.ca">Badrul Masud </a><br> <a href="mailto:Quan.Cui@ualberta.ca">Quan Cui </a><br>|
|WATFLOOD-MH  |	Nelson-Churchill  |	Manitoba Hydro |	<a href="mailto:kkoenig@hydro.mb.ca">Kristina Koenig  </a><br> <a href="mailto:swruth@hydro.mb.ca">Shane Wruth  </a><br> <a href="mailto:pslota@hydro.mb.ca">Phillip Slota  </a><br> <a href="mailto:mgervais@hydro.mb.ca">Mark Gervais  </a><br> <a href="mailto:ksagan@hydro.mb.ca">Kevin Sagan  </a><br>|
|VIC  |	Lower Nelson River  |	UNBC |	<a href="mailto:stephen.dery@unbc.ca">Stephen Dery </a><br> <a href="mailto:lilhare@unbc.ca">Rajtantra Lilhare </a><br>|
|MESH  |	Saskatchewan river & Nelson river  |	ECCC |	<a href="mailto:bruce.davison@canada.ca">Bruce Davison </a><br> <a href="mailto:fuad.yassin@usask.ca">Fuad Yassin  </a><br>|
|HEC-HMS  |	Red River  |	Strategic Consulting |	<a href="mailto:umpokors@myumanitoba.ca">Scott Pokorny </a><br> <a href="mailto:hank@strategiccc.ca">Henry David (Hank) Venema </a><br>|
|RAVEN  |	To be determined  |	University of Waterloo |	<a href="mailto:jrcraig@uwaterloo.ca">James Craig </a><br> <a href="mailto:juliane.mai@uwaterloo.ca">Juliane Mai </a><br> <a href="mailto:mahkameh.taheri@uwaterloo.ca">Mahkameh Taheri </a><br>|
|SUMMA  |	Nelson Churchill  |	University of Saskatchewan |	<a href="mailto:martyn.clark@usask.ca">Martyn Clark </a><br> <a href="mailto:wouter.knoben@usask.ca">Wouter Knoben </a><br> <a href="mailto:shervan.gharari@usask.ca">Shervan Gharari </a><br>|
|Noah-MP  |	Assiniboine & Red rivers |	Western University |	<a href="mailto:mnajafi7@uwo.ca">Mohammad Reza Najafi  </a><br>|
|HBV-EC  |	To be determined  |	Manitoba Infrastructure |	<a href="mailto:fisaha.unduche@gov.mb.ca">Fisaha Unduche </a><br> <a href="mailto:habtamu.tolossa@gov.mb.ca">Habtamu Tolossa </a><br>|
|WATFLOOD-MI  |	To be determined  |	Manitoba Infrastructure |	<a href="mailto:fisaha.unduche@gov.mb.ca">Fisaha Unduche </a><br> <a href="mailto:habtamu.tolossa@gov.mb.ca">Habtamu Tolossa </a><br>|

# Contributers

| Institutions | Contact persons |
| :---: | :---: |  
|ECCC |<a href="mailto:frank.seglenieks@canada.ca">Frank Seglenieks </a> <br> <a href="mailto:daniel.princz@canada.ca">Daniel Princz </a> <br> <a href="mailto:andreguy.temgoua@canada.ca">André Guy Temgoua </a><br> <a href="mailto:narayan.shrestha@canada.ca">Narayan Shrestha </a><br>|
|University of Waterloo | <a href="mailto:btolson@uwaterloo.ca">Bryan Tolson </a>|
|University of Saskatchewan | <a href="mailto:mohamed.elshamy@usask.ca">Mohamed Elshamy </a><br> <a href="mailto:saman.razavi@usask.ca">Saman Razavi </a><br> <a href="mailto:laila.balkhi@usask.ca">Laila Balkhi </a><br> <a href="mailto:hayley.carlson@usask.ca">Hayley Carlson </a><br>|
|TransAlta | <a href="mailto:German_Mojica@transalta.com">German Mojica </a>|
|Alberta Environment and Parks (AEP) | <a href="mailto:Khaled.Akhtar@gov.ab.ca">Khaled Akhtar </a>|


# Project phases (tentative)  

Four phases are envisaged for the research project at the pre-proposal stage. Contributing modelers are welcome to make suggestions and recommendations at the early stages of the project (2019-20), to help define the scope and objectives. For each phase, we would like the modelers to output and report every variables or processes simulated in their model. 

 

**Phase 0:** Uncalibrated model run (with user-defined parameter sets).

In Phase 0, the models should not go through any parameter estimation, i.e. manual or automatic. The modelers should report streamflow for the selected hydrometric stations in the watershed at a daily time step. 

------
**Phase 1:** Calibrated model run at unregulated (headwater) gauges. 

Phase 1 vs Phase 0 will help assess the calibration efforts. In Phase 1, the modelers should output all variables at a daily time step. They will report as a time series streamflow for selected hydrometric gauge stations in the watershed and spatial averages for the simulation results that are not point variables (e.g. evapotranspiration). State-flux relationships will be examined based on the variables outputted to gain a better understanding of the processes modeled (internal model structure) and the plausible advantages/limitations of the algorithms used. Modelers should also report the standard name of the variables together with the name of the algorithm chosen in their model for the simulation of each process (e.g. modified Jensen-Haise/McGuiness, modified Hargreaves-Samani, Priestly-Taylor or FAO Penman-Monteith for evapotranspiration in HYPE). Knowing the mathematical formulation of each process, the variables (not just processes) outputted may be used to reconstruct the internal hydrologic processes (e.g. water storage at different levels, conductivity, subsurface lateral inflow and outflow, actual evaporation, actual transpiration, deep percolation may be used to reconstruct soil moisture depending on the algorithm implemented in the model).  

------
**Phase 2:** Calibrated model run at regulated gauges. 

Phase 2 vs Phase 1 will show up the impact of human influence through flow regulation on the catchment hydrology. The modelers should output all variables at a daily time step. They will report as a time series streamflow for selected hydrometric gauge stations in the watershed and spatial averages for the simulation results that are not point variables (e.g. evapotranspiration). Outputs specific to the regulation such as water levels and reservoir releases should also be reported at a daily time step. 

------
**Phase 3:** Ensemble modeling of climate change impacts using models developed in Phase 1 and/or Phase 2. 

In Phase 3, a set of 19 bias-corrected climate model simulations will be used to drive streamflow predictions under changing climate conditions following RCP4.5 and RCP8.5 representative concentration pathways.  

Learning from approaches developed in the climate science community for multi-model ensemble averaging and uncertainty reduction (e.g. “reliability ensemble averaging” [Giorgi & Mearns 2002, 2003], B-REA [Tebaldi et al. 2004, 2005] or fully Bayesian approaches) robust weighting schemes will be developed to reduce the uncertainty and provide a probabilistic assessment of climate change impact on streamflow prediction.  

Storage-flux relationships will also be examined to understand (i) whether the relationships are non-stationary in time and (ii) the models are well suited for streamflow prediction under climate change. Thus, the established relationships obtained in Phase 3 will be compared to those obtained from Phase 1 or Phase 2 to derive sound conclusions on the reliability of the simulated processes under climate change conditions.  

 

From Phase 1 statistical models or simple conceptual hydrologic models like GR4J with the CemaNeige snow module or LBRM may be used to establish a baseline (benchmark) for model comparison. 

Though it would be best if all modelers participate in all phases, a modeling team may choose to participate in Phase 1, Phase 2 or both. Same applies to Phase 3. Their simulation results model will be analyzed and included in the inter-model comparison for the phases they contributed to. 

# Deliverables
i- An ensemble streamflow prediction will be available for the selected sub-watersheds; 

ii- Models will be ranked and the better models are identified based on streamflow metrics and hydrologic signatures; 

iii- Differences among model performances will be better understood from the representation of the internal processes (model structure); 

iv- Internal processes to improve in the contributing models will be identified and plausible algorithms for process improvement will be recommended to modelers/model developers; 

v- The robustness of the hydrologic models for climate change impact projections will be examined; 

vi- Co-authored research papers on model performance, limitations/plausible improvements to model structure, regulation impact and ensemble streamflow projections under future climate change will be published. 

# Reporting

Beyond surface runoff, all variables (e.g. SWE, evapotranspiration, soil moisture, recharge) should be reported for each project phase at a daily time step. Modelers should also report the standard name of all variables and the name of the algorithms implemented for the hydrologic processes included in their models. 

# Design of the modeling experiments 

A private GitHub repository will be used for data sharing. Only modelers involved in the project will have a secure access to the data. Monthly meetings will be scheduled, and modelers will report on the advancement of their work and discuss challenges. Deadlines will be set for reporting for Phase 0 through Phase 3 and modelers are encouraged to send their simulations to the project leader by the deadlines.  
## Input data<br>
	
A standardized set of geophysical data and meteorological/climate forcing data will be provided for this research project.
	
### DEM and derived products<br>
We can choose either HydroSHEDS data products at 3s resolution (~90 m) or the MERIT Hydro data products.  


UC-HAL team can provide the routing to be used by other teams. This will ensure consistency in the watershed and sub-basins delineation (i.e. across models using a sub-watershed discretization the sub-basins will have the same size). However, other teams are welcome to use their own routing derived from the standardized DEM products if preferred.  
MERIT Hydro is a new global flow direction map at 3 arc-second resolution (~90 m at the equator) derived from the latest elevation data (MERIT DEM) and water body datasets (G1WBM, GSWO, and OpenStreetMap).  It contains flow direction, flow accumulation, hydrologically adjusted elevations, and river channel width (http://hydro.iis.u-tokyo.ac.jp/~yamadai/MERIT_Hydro/). The MERIT DEM was developed by removing multiple error components (absolute bias, stripe noise, speckle noise, and tree height bias) from the existing spaceborne DEMs (SRTM3 v2.1 and AW3D-30m v1). It represents the terrain elevations at a 3sec resolution (~90m at the equator), and covers land areas between 90N-60S, referenced to EGM96 geoid. Hydrologically adjusted DEM is now available as a component of MERIT Hydro datasets (http://hydro.iis.u-tokyo.ac.jp/~yamadai/MERIT_DEM/). For access we shall contact Dan Yamadai at yamadai@iis.u-tokyo.ac.jp.
	
### Land use/land cover<br>
North American Land Change Monitoring System (NALCMS) at 30m resolution or 2010 Land Cover of Canada at 30m resolution.


In case the modelling domain covers the US part of the Nelson-Churchill river basin we will use the NALCMS land cover map. If the selected sub-basins do not extend to US, we use the 2010 Land Cover of Canada developed by the Canada Centre for Remote Sensing at Natural Resources Canada. 
2010 Land cover of Canada is 30 m resolution dataset of Canada’s 15 land cover classes from Landsat-7 images taken between 2009 and 2011 for cloud- and snow-free national coverage. It was developed as the Canada contribution to the North American Land Change Monitoring System (NALCMS) initiative and will be updated every five years, or more frequently. It is publicly downloadable from https://open.canada.ca/data/en/dataset/c688b87f-e85f-4842-b0e1-a8f79ebf1133.  
NALCMS is available at both 250 m and 30 m resolution. The higher spatial resolution product will be used. NALCMS provides a harmonized view of the physical cover of Earth's surface across the North American continent based on 2010 Landsat satellite imagery. It is a result of a collaborative initiative between Canada, US and Mexico. It comprises nineteen Level II land cover classes defined using the Land Cover Classification System (LCCS) standard from UN-FAO. It is publicly available from http://www.cec.org/tools-and-resources/map-files/land-cover-2010-landsat-30m.  

### Soil data
Global Soil Dataset for Earth System Modelling (GSDE)


GSDE is based on the Soil Map of the World and various regional and national soil databases, including soil attribute data and soil maps. It provides soil information including soil particle-size distribution, organic carbon, and nutrients, etc. There are for 11 types of soil general information for soil profiles and 34 soil properties for 8 depths. The data set is provided at 30 arc-seconds resolution (~1km). The vertical variation of soil property was captured by eight layers to the depth of 2.3 m (i.e. 0- 0.045, 0.045- 0.091, 0.091- 0.166, 0.166- 0.289, 0.289- 0.493, 0.493- 0.829, 0.829- 1.383 and 1.383- 2.296 m). It can be downloaded from http://globalchange.bnu.edu.cn/research/soilw#download.  

### Water table depth  

Water table depth needed by some hydrologic models (e.g. HYPE) can be derived from an observed averaged water table depth (derived from 837,956 sites across Canada and 567,946 sites in US) and model simulations published by Fan et al. Global Patterns of Groundwater Table Depth. Science 339, 940 (2013) DOI: 10.1126/science.1229881. The data are downloadable from https://glowasis.deltares.nl/thredds/catalog/opendap/opendap/Equilibrium_Water_Table/catalog.html. 

### Meteorological/ Climate forcing data
WFDEI-GEM-CaPA (3-hourly x 0.125ᵒ - 1979- 2016) or ERA-5 reanalysis product (1979-near real time, 1-hourly, 30km-grid).


WFDEI-GEM-CaPA is a collaborative initiative of the University of Saskatchewan and Environment and Climate Change Canada. It is a merged product of the EU WATCH ERA-Interim reanalysis (WFDEI) with long temporal coverage but biased over Canada relative observations, and the high-resolution forecasts of the Global Environmental Multiscale (GEM) atmospheric model and the Canadian Precipitation Analysis (CaPA) reanalysis with a short historical record. Thus WFDEI-GEM-CaPA is a less-biased long record product. WFDEI was bias-corrected against GEM-CaPA at 3h x 0.125ᵒ resolution during 2005-2016, followed by a hindcast of WFDEI-GEM-CaPA from 1979. Following a 365_day calendar (February 29 is removed), WFDEI-GEM-CaPA is available from January 1, 1979 to December 31, 2016 at a 3-hourly step. Seven atmospheric variables namely total precipitation (rainfall + snowfall) in kg.m-2s-1, surface pressure in Pa, air temperature at 40m in K, specific humidity at 40m in kg/kg, surface downwelling longwave radiation in W.m-2, wind speed at 40m m.s-1 and surface downwelling shortwave radiation in W.m-2 are provided. The set of data is downloaded from https://www.frdr.ca/repo/handle/doi:10.20383/101.0111 and is referenced as follow: Asong, Zilefac Elvis; Wheater, Howard; Pomeroy, John; Pietroniro, Alain; Elshamy, Mohamed, "A Bias-Corrected 3-hourly 0.125 Gridded Meteorological Forcing Data Set (1979 – 2016) for Land Surface Modeling in North America," 2018, doi:10.20383/101.0111 

ERA5 dataset from ECMWF is available for public use (1979 to within 3 months of real time). It provides hourly estimates of a large number of atmospheric, land and oceanic climate variables using a significantly more advanced 4Dvar assimilation scheme. The data is a 30km grid resolution and resolves the atmosphere using 137 levels from the surface up to a height of 80km. The entire ERA5 dataset from 1950 to present is expected to be available for use in 2020. ERA5 combines vast amounts of historical observations into global estimates using advanced modelling and data assimilation systems. It may be downloaded from the Download ERA5 from the Copernicus Climate Change Service (C3S) Climate Date Store (https://cds.climate.copernicus.eu/#!/search?text=ERA5&type=dataset). 

All hydrological models will be calibrated and validated using the WFDEI-GEM-CaPA dataset or ERA5 depending on modelers’ agreement.  

For future climate change impact predictions, we will use a set of 19 GCM projections spanning a range of plausible future climates under RCP4.5 and RCP8.5 representative concentration pathways. The GCM simulations are already bias-corrected by Ouranos Inc using a cumulative quantile mapping method and readily available from UC-HAL.

### Remote sensing data for model validation
**(to be determined)** 

We suggest validating hydrologic processes such as snow water equivalent (SWE), evapotranspiration, soil temperature, surface storage, soil moisture, groundwater recharge. The selection of remotely sensed products for the validation of key hydrologic processes will be finalized by the launch date of this project (Fall 2020). 

### Hydrometric data 

These sets of streamflow gauging data will be derived from the Water Survey Canada and USGS databases. The selected gauge stations should have a drainage area above 200 km2. 2/3 of the gauge stations will be used for model calibration and the remaining stations for model validation.  

## Model calibration and validation 

The gauging stations for model calibration and validation will be selected after the modelers have all agreed on the modeling domain. We may consider doing a spatial and/or temporal validation depending on the temporal and spatial coverage of the gauge data over the selected sub-basin and modelers’ opinion. The time period for calibration and/or validation will be determined later depending of the gauging stations selection and data availability. 

### Metrics for model calibration and validation

Besides daily flow we propose validating the hydrologic models using also flow signatures such as low streamflow (Q5), high streamflow (Q95) and the slope of flow duration curve calculate using Q75 and Q25. In the following checklist the modelers are invited to choose what metrics they would prefer for performance assessment and the formulation of the objective function. 
Depending on the availability of soft data and remote sensing products for hydrology we will consider validating key hydrologic processes as well. Suggestions from modelers are welcome on the hydrological processes to be validated against observations/remote sensing data and the data available for this purpose.

# Nelson-MiP survey  
**To be added (if needed)**

# 19 CMIP5 bias-corrected GCMs for Phase 3
|Ref |	GCMs |	Description |	Resolution |	RCP 4.5 |	RCP 8.5 |
| :---: | :---: |  :---: | :---: | :---: | :---: |
|A10 |	ACCESS 1.0 |	Australian Community Climate and Earth System Simulator 1.0 |	1.25ºx1.87º |	X |	X |
|A13 |	ACCESS 1.3 |	Australian Community Climate and Earth System Simulator 1.3 |	1.25ºx1.87º |	X |	X |
|CE2 |	CanESM2 |	The Second Generation Canadian Earth System Model |	2.79ºx2.81º |	X |	|
|CMM |	CMCC-CM |	Centro Euro-Mediterraneio per I Camibamenti Climatici-Climate Model |	0.78ºx0.75º |	X |	|
|CMS |	CMCC-CMS |	Centro Euro-Mediterraneio per I Camibamenti Climatici-Climate Model with a resolved stratosphere |	3.71ºx3.75º |	|	X |
|CN5 |	CNRM-CM5 |	The Centre National de Recherches Meterologiques Coupled global climate Model version 3  |	1.40ºx1.40º |	X |	|
|GF3 |	GFDL-CM3 |	NOAA Geophysical Fluid Dynamics Laboratory-Coupled Model Version 3 |	2.0ºx2.5º |	X |	|
|IAL |	IPSL-CM5A-LR |	Institut Pierre-Simon Laplace-earth system model for the 5th IPCC report-Low Resolution |	1.89ºx3.75º |	X |	X |
|INM |	INMCM4 |	Russian Institute for Numerical Mathematics-Climate Model 4 |	1.5ºx2.0º |	X |	|
|MI5 |	MIROC5 |	Model for Interdisciplinary Research on Climate 5  |	1.4ºx1.4º |	X |	X |
|MIC |	MIROC-ESM-CHEM |	Model for Interdisciplinary Research-Earth System Model-atmospheric chemistry coupled version |	2.79ºx2.81º |	|	X |
|MIE |	MIROC-ESM |	Model for Interdisciplinary Research-Earth System Model |	2.79ºx2.81º |	|	X |
|MR3 |	MRI-CGCM3 |	Meteorological Research Institute-atmosphere-ocean Coupled General Circulation Model 3  |	1.12ºx1.12º |	X |	X |
|NOE |	NorESM1-M |	Norwegian Earth System Model–Medium Resolution |	1.89ºx2.5º |	X |	|

# Mailing list
    Tricia Stadnyk <tricia.stadnyk@ucalgary.ca>; Ajay Bajracharya <ajay.bajracharya@ucalgary.ca>; Oyémonbadé Awoye <oyemonbade.awoye@ucalgary.ca>; Ameer Muhammad <ameer.muhammad@wsask.ca>; Curtis Hallborg <curtis.hallborg@wsask.ca>; Masoud Asadzadeh <Masoud.Asadzadeh@umanitoba.ca>; Monireh Faramarzi <faramarz@ualberta.ca>; Kristina Koenig <kkoenig@hydro.mb.ca>; Stephen Dery <stephen.dery@unbc.ca>; Rajtantra Lilhare <lilhare@unbc.ca>; Bruce Davison <bruce.davison@canada.ca>; Scott Pokorny <umpokors@myumanitoba.ca>; Henry David (Hank) Venema <hank@strategiccc.ca>; James Craig <jrcraig@uwaterloo.ca>; Martyn Clark <martyn.clark@usask.ca>; Wouter Knoben <wouter.knoben@usask.ca>; Shervan Gharari <shervan.gharari@usask.ca>; Mohammad Reza Najafi <mnajafi7@uwo.ca>; Fisaha Unduche <Fisaha.Unduche@gov.mb.ca>; Bryan Tolson <btolson@uwaterloo.ca>; Juliane Mai <juliane.mai@uwaterloo.ca>; Saman Razavi <saman.razavi@usask.ca>; Mohamed Elshamy <mohamed.elshamy@usask.ca>; Frank Seglenieks <frank.seglenieks@canada.ca>;Daniel Princz <daniel.princz@canada.ca>; André Guy Temgoua <andreguy.temgoua@canada.ca>; Shane Wruth <swruth@hydro.mb.ca>; Phillip Slota <pslota@hydro.mb.ca>; Mark Gervais <mgervais@hydro.mb.ca>; Kevin Sagan <ksagan@hydro.mb.ca>; Pouya Khalili <khalili@ualberta.ca>; Badrul Masud <masud@ualberta.ca>; Fuad Yassin <fuad.yassin@usask.ca>; German Mojica <German_Mojica@transalta.com>; Khaled Akhtar <Khaled.Akhtar@gov.ab.ca>; Laila Balkhi <laila.balkhi@usask.ca>; Hayley Carlson <hayley.carlson@usask.ca>; Yinlong Huang <huangy32@myumanitoba.ca>; Habtamu Tolossa <habtamu.tolossa@gov.mb.ca>; Quan Cui <Quan.Cui@ualberta.ca>; Narayan Shrestha <narayan.shrestha@canada.ca>; Mahkameh Taheri <mahkameh.taheri@uwaterloo.ca>
