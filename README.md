# Detecting Crested Wheatgrass Using Remote Sensing 2
This repository contains the code used in this [paper](https://www.sciencedirect.com/science/article/pii/S1195103626000029?via%3Dihub). It includes all relevant scripts, along with the required Excel/CSV files needed to run them. Each script is accompanied by an extended description explaining its purpose and functionality.

The repository also includes Google Earth Engine (GEE) JavaScript files developed to generate time-series data using both PlanetScope and Sentinel imagery. The shared GEE links contain the scripts as well as the associated asset links, which is why sharing the GEE links directly is the most convenient approach.

Sentinel-2A time series
1. https://code.earthengine.google.com/475ec2439d7e57e83b13eedf231bfe12 (TimeSeriesUsingNDVI_Sentinel2A_24_19_iNaturalists)
2. https://code.earthengine.google.com/56e20bcae75f29fa8daa48a6e3e49045 (TimeSeriesUsingRGRS2_Sentinel2A_24_19_iNaturalists)
3. https://code.earthengine.google.com/af5bc36b46bb6971c5224c828f019417 (TimeSeriesUsingWSIS2_Sentinel2A_24_19_iNaturalistss)

PlanetScope SuperDove time series
1. https://code.earthengine.google.com/24f24468b15b18838ddb9816f4f78295 (TimeSeriesUsingNDVI_PlanetScope_24_19_iNaturalists)
2. https://code.earthengine.google.com/37abbbc2e495edab10f235191973b437 (TimeSeriesUsingPRIPS_PlanetScope_24_19_iNaturalists)
3. https://code.earthengine.google.com/4c32e005f3db7a4e8fb6748a78472417 (TimeSeriesUsingRGRS2_PlanetScope_24_19_iNaturalists)


I also uploaded all the Python scripts that were used to do the time series classification using different spectral indices and using PlanetScope SuperDove and Sentinel-2A. So, the order of the files are these: you have to run the GEE JavaScript files first to get the time series data. Then, you have to run the Python scripts that use that data.






