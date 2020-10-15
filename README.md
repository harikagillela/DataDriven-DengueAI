# DataDriven-DengueAI

DengAI: Predicting Disease Spread
Predict the Dengue cases for each (city, year, weekofyear)

You are provided the following set of information on a (year, weekofyear) timescale:

(Where appropriate, units are provided as a _unit suffix on the feature name.)

City and date indicators

city – City abbreviations: sj for San Juan and iq for Iquitos
<br>
week_start_date – Date given in yyyy-mm-dd format
<br>
NOAA's GHCN daily climate data weather station measurements

station_max_temp_c – Maximum temperature
<br>
station_min_temp_c – Minimum temperature
<br>
station_avg_temp_c – Average temperature
<br>
station_precip_mm – Total precipitation
<br>
station_diur_temp_rng_c – Diurnal temperature range

PERSIANN satellite precipitation measurements (0.25x0.25 degree scale)
<br>
precipitation_amt_mm – Total precipitation

NOAA's NCEP Climate Forecast System Reanalysis measurements (0.5x0.5 degree scale)

reanalysis_sat_precip_amt_mm – Total precipitation
<br>
reanalysis_dew_point_temp_k – Mean dew point temperature
<br>
reanalysis_air_temp_k – Mean air temperature
<br>
reanalysis_relative_humidity_percent – Mean relative humidity
<br>
reanalysis_specific_humidity_g_per_kg – Mean specific humidity
<br>
reanalysis_precip_amt_kg_per_m2 – Total precipitation
<br>
reanalysis_max_air_temp_k – Maximum air temperature
<br>
reanalysis_min_air_temp_k – Minimum air temperature
<br>
reanalysis_avg_temp_k – Average air temperature
<br>
reanalysis_tdtr_k – Diurnal temperature range

Satellite vegetation - Normalized difference vegetation index (NDVI) - NOAA's CDR Normalized Difference Vegetation Index (0.5x0.5 degree scale) measurements

ndvi_se – Pixel southeast of city centroid
<br>
ndvi_sw – Pixel southwest of city centroid
<br>
ndvi_ne – Pixel northeast of city centroid
<br>
ndvi_nw – Pixel northwest of city centroid
