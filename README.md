# Introduction

These files are part of the data delivery for the ESA 4DMED hydrology project 
(https://www.4dmed-hydrology.org/) by Planet Labs PBC (VanderSat). This data set includes Soil Moisture, Land Surface Temperature and vegetation Optical Depth for the 4DMED spatial domain and time period (2015-2021). If you use the data please include the following reference:

*Jaap Schellekens, Tessa Kramer, Michel van Klink, Robin van der Schalie, Yoann Malbeteau, Arjan Geers,  Richard de jeu. (2022) A 1KM dataset for the Mediterranean terrestrial region of Soil Moisture, Land Surface Temperature and Vegetation Optical Depth from passive microwave data. DOI xxxxx. Planet Labs PBC/VanderSat B.V., ESA Contract No. 4000136272/21/I-EF*


# Data

This dataset consists of the following products for the 4DMED domain:


- TEFF-AMSR2-ASC_V4.0_1000
    - Land surface temperature daytime (13:30 solar time) at 1 km
- TEFF-AMSR2-DESC_V4.0_1000 
    - Land surface temperature nighttime (01:30 solar time) at 1 km
- QF-TEFF-AMSR2-ASC_V4.0_1000 
    - Land surface temperature daytime quality flag
- QF-TEFF-AMSR2-DESC_V4.0_1000 
    - Land surface temperature nighttime quality flag
- VOD-AMSR2-C1-DESC_V4.0_1000 
    - C1 band Vegetation Optical Depth (nighttime, 01:30 solar time) at 1km
- VOD-AMSR2-X-DESC_V4.0_1000 
    - X band Vegetation Optical Depth (nighttime, 01:30 solar time) at 1km
- SM-AMSR2-C1-DESC_V4.0_1000 
    - C1 band soil moisture (nighttime, 01:30 solar time) at 1km
- SM-AMSR2-X-DESC_V4.0_1000 
    - X band soil moisture (nighttime, 01:30 solar time) at 1km
- SM-SMAP-L-DESC_V4.0_1000 
    - L band soil moisture (nighttime) at 1km
- QF-SM-AMSR2-C1-DESC_V4.0_1000 
    - C1 band soil moisture (nighttime, 01:30 solar time) at 1km
- QF-SM-AMSR2-X-DESC_V4.0_1000 
    - X band soil moisture (nighttime, 01:30 solar time) at 1km
- QF-SM-SMAP-L-DESC_V4.0_1000 
    - L band soil moisture (nighttime) at 1km
- CORRELATION MAPS


All files are archived into one zip file per product (or product group). Each individual netcdf file consists of one observation for the whole domain. If you need you can combine the files into one file using the cdo software (e.g. `cdo -f nc4c mergetime *.nc outfile.nc`).


# License

The data for 4DMED is released under the Creative Commons license: CC BY-NC-SA 4.0 (https://creativecommons.org/licenses/by-nc-sa/4.0/)

- Contains modified Copernicus Sentinel data 2015-2020

- Contains modified JAXA GCOM-W1/AMSR2 data 2012-2020

- Contains modified SMAP L1B Radiometer data: Piepmeier, J. R., P. Mohammed, J. Peng, E. J. Kim, G. De Amici, J. Chaubell, and C. Ruf. 2020. SMAP L1B Radiometer Half-Orbit Time-Ordered Brightness Temperatures, Version 4,5. Boulder, Colorado USA. NASA National Snow and Ice Data Center Distributed Active Archive Center. doi: https://doi.org/10.5067/ZHHBN1KQLI20



# Contact

Jaap Schellekens: jaap@planet.com


# Further information

More information on the data and the flags can be found at https://docs.vandersat.com 
