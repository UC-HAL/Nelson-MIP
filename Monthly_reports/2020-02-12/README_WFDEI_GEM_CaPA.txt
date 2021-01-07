This README.txt file was generated on <20180906> by <ZILEFAC ELVIS ASONG >

---------------------------------------------
FOLDER/FILE ORGANIZATION & DATA-SPECIFIC INFORMATION
---------------------------------------------
The main folder, CCRN, contains 3 sub-folders as explained below. Each sub-folder contains 7 files corresponding to 7 variables. The various data sets are described in the Methods section below

1. Folder/File list of CCRN folder

	A. Sub-folder: WFDEI-GEM_1979_2016
	   Dataset name: WFDEI-GEM-CaPA
	   Time period: 1979-01-01 00:00:00 to 2016-12-31 21:00:00 (YYYY-MM-DD hh:mm:ss)
	   Short description: This sub-folder contains the bias corrected data at 0.125 degrees. The corrected WFDEI-GEM-CaPA data reflect 40m variables in GEM-CaPA.

		i.   Filename: pr_WFDEI_GEM_1979_2016-final.nc
		     Short description: total precipitation (rainfall + snowfall, kg m-2 s-1)
		   
		ii.  Filename: ps_WFDEI_GEM_1979_2016-final.nc
		     Short description: surface pressure (Pa)
			
		iii. Filename: tas_WFDEI_GEM_1979_2016-final.nc
		     Short description: air temperature at 40m (K)
			
		iv.  Filename: huss_WFDEI_GEM_1979_2016-final.nc
		     Short description: specific humidity at 40m (kg/kg)
		
		v.   Filename: rlds_WFDEI_GEM_1979_2016-final.nc
		     Short description: surface downwelling longwave radiation (W m-2)
		
		vi.  Filename: sfcWind_WFDEI_GEM_1979_2016-final.nc
		     Short description: wind speed at 40m (m s-1)
		
		vii. Filename: rsds_WFDEI_GEM_1979_2016-final.nc
		     Short description: surface downwelling shortwave radiation (W m-2)

	B. Sub-folder: WFDEI_1979_2016
	   Dataset name: WFDEI
	   Time period: 1979-01-01 00:00:00 to 2016-12-31 21:00:00 (YYYY-MM-DD hh:mm:ss)
	   Short description: This sub-folder contains the original WFDEI data, but has been interpolated to 0.125 degrees resolution.

		i.   Filename: pr_WFDEI_Obs_1979_2016.nc
		     Short description: total precipitation (rainfall + snowfall, kg m-2 s-1)
		
		ii.  Filename: ps_WFDEI_Obs_1979_2016.nc
		     Short description: surface pressure (Pa)
		
		iii. Filename: tas_WFDEI_Obs_1979_2016.nc
		     Short description: air temperature at 2m (K)
		
		iv.  Filename: huss_WFDEI_Obs_1979_2016.nc
		     Short description: specific humidity at 2m (kg/kg)
		
		v.   Filename: rlds_WFDEI_Obs_1979_2016.nc
		     Short description: surface downwelling longwave radiation, W m-2)
		
		vi.  Filename: sfcWind_WFDEI_Obs_1979_2016.nc
		     Short description: wind speed at 10m (m s-1)
		
		vii. Filename: rsds_WFDEI_Obs_1979_2016.nc
		     Short description: surface downwelling shortwave radiation (W m-2)

	C. Sub-folder: GEM_CaPA_2005_2016
	   Dataset name: GEM-CaPA
	   Time period: 2005-01-01 00:00:00 to 2016-12-31 21:00:00 (YYYY-MM-DD hh:mm:ss)
	   This sub-folder contains the original GEM-CaPA data used for correcting WFDEI, and has been interpolated to 0.125 degrees resolution.

		i.   Filename: GEM_pr_2005_2016.nc
		     Short description: total precipitation (rainfall + snowfall, kg m-2 s-1)
		
		ii.  Filename: GEM_ps_2005_2016.nc
		     Short description: surface pressure (Pa)
		
		iii. Filename: GEM_tas_2005_2016.nc
		     Short description: air temperature at 40m (K)
		
		iv.  Filename: GEM_huss_2005_2016.nc
		     Short description: specific humidity at 40m (m s-1)
		
		v.   Filename: GEM_rlds_2005_2016.nc
		     Short description: surface downwelling longwave radiation, W m-2)
		
		vi.  Filename: GEM_sfcWind_2005_2016.nc
		     Short description: wind speed at 40-metre (m s-1)
		
		vii. Filename: GEM_rsds_2005_2016.nc
		     Short description: surface downwelling longwave radiation (W m-2)

2. Data-specific information applicable to all files
   File formats: NetCDF
   Time zone: UTC (all data start at 00:00:00)
   Calendar: 365_day (February 29 is removed)
   Missing value flag: 1.e+20f

---------------------------------------------
METHODOLOGICAL INFORMATION
---------------------------------------------

1. Description of methods used for collection/generation of data and processing:

The methodology is described fully in Asong et al. (2018). A short summary is provided below.

The EU WATCH ERA-Interim reanalysis—WFDEI (Weedon et al., 2014) 3h*0.5ᵒ dataset (1979-2016) was bias corrected against the high resolution forecasts of the Global Environmental Multiscale (GEM) atmospheric model (Yeh et al., 2002) and the Canadian Precipitation Analysis (CaPA) reanalysis (Mahfouf et al., 2007). The GEM-CaPA data used to correct WFDEI were extracted for the period 2005-2016. Note that the GEM 40 m variables are used to correct WFDEI surface variables directly (2m temperature, 2m specific humidity, and 10m wind speed). Therefore, the corrected WFDEI-GEM-CaPA data reflect 40m variables.

The initial purpose of the bias correction was to provide synthetic retrospective meteorology for large-scale hydrological modelling over the Mackenzie and Saskatchewan River Basins. The MESH model (https://wiki.usask.ca/display/MESH/About+MESH) for these basins has been set up at 0.125ᵒ resolution, thus all data sets are also interpolated then corrected at this resolution. CaPA is available at 6-hourly temporal resolution. Initially, the accumulated precipitation at each 6-hour time step was linearly interpolated to produce precipitation for every hour within the 6-hour period. Subsequently, bias correction is done after aggregating 1-hourly GEM-CaPA estimates to 3-hourly and interpolating both WFDEI and GEM-CaPA to 10km (0.125ᵒ) resolution. For bias correction, a multi-stage approach was implemented as described below:

1) A multivariate generalization of the quantile mapping technique (Cannon et al., 2018) was implemented to bias-correct WFDEI against GEM-CaPA at 3h*0.125ᵒ resolution during the 2005 - 2016 period
2) Models were fitted to data for each calendar month while accounting for inter-variable dependence structure
3) Using the fitted models (2005-2016), a hindcast was made of WFDEI between 1979-2004
4) Finally, corrected WFDEI data derived from the fitted models for the  2005-2016 and 1979-2004 periods were merged to obtain the bias-corrected WFDEI-GEM-CaPA product (1979-2016)

It is worth noting that WFDEI has two precipitation sources (CRU and GPCC). We had to use the CRU data set because it goes to 2016 while GPCC had been only updated until 2013 at the time of our analysis.

References:
Asong, Z. E., H. S. Wheater, J. Pomeroy, A. Pietroniro, M. Elshamy, and D. Princz (2018), WFDEI-GEM-CaPA: A 38-year High-Resolution Meteorological Forcing Data Set for Land Surface Modeling in North America, manuscript in prep, targeted for submission to Earth System Science Data (ESSD).
Cannon, A. J.: Multivariate quantile mapping bias correction: An N-dimensional probability density function transform for climate model simulations of multiple variables, Clim Dyn, 50, 31–49, doi:10.1007/s00382-017-3580-6, 2018.
Mahfouf, J.-F., Brasnett, B. and Gagnon, S. (2007). A Canadian precipitation analysis (CaPA) project: Description and preliminary results. Atmosphere-Ocean, 45: 1–17.
Weedon, G.P., G. Balsamo, N. Bellouin, S. Gomes, M. J. Best, and P. Viterbo, 2014: The WFDEI meteorological forcing data set: WATCH Forcing Data methodology applied to ERA Interim reanalysis data. Water Resour. Res., 50, 7505–7514, doi:10.1002/2014WR015638.
Yeh, K., J. Côté, S. Gravel, A. Méthot, A. Patoine, M. Roch, and A. Staniforth, 2002: The CMC–MRB Global Environmental Multiscale (GEM) Model. Part III: Nonhydrostatic Formulation. Mon. Wea. Rev., 130, 339–356, https://doi.org/10.1175/1520-0493(2002)130<0339:TCMGEM>2.0.CO;2 

2. Instrument- or software-specific information needed to interpret the data:

The data can be manipulated and/or visualized by using any of the freely available tools at https://www.unidata.ucar.edu/software/netcdf/software.html
