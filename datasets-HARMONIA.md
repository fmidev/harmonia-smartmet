# Datasets from Copernicus for HARMONIA project

* ERA5 hourly data from 1979 to present: updated daily reanalysis (5 day time delay) 
* ECSF, ECBSF, ECB2SF seasonal forecasts: 215 daily forecasts 7 months ahead (|B| and |B2|: bias adjusted forecasts)
* CAMS, CAMSEU, CAMSEURA atmospheric composition model output data: daily 5-day forecasts with hourly data
* dissemination thru smartmet-server (https://github.com/fmidev/smartmet-server) check out wiki pages for [Timeseries-plugin](https://github.com/fmidev/smartmet-plugin-timeseries/wiki) and [WMS (Dali & WMS) plugin](https://github.com/fmidev/smartmet-plugin-wms/wiki/SmartMet-plugin-WMS-(Dali-&-WMS))!

|dataset producer|availability|
|:---|:---|
|ERA5| daily reanalysis from 5 days ago |
|ECSF, ECBSF, ECB2SF| daily forecasts 7 months ahead |
|CAMS, CAMSEURA, CAMSEU| daily 5-day forecasts with hourly data|

# C3S Variables   

Bolded variables are assumed to be of most interest to HARMONIA project based on WP2.1 Workshop Report and other. 

| Available C3S variables|ERA5|ECSF|ECBSF|ECB2SF| 
|:-----------------------------------------------------------|:---:|:----:|:-----:|:------:|
| **Air temperature (2 m)**                                  | x | x | x | x |
| **Soil temperature level 1 (ground temperature)**          | x | x | x | x |      
| Soil temperature level 2                                   | x | x | x | x |      
| Soil temperature level 3                                   | x | x | x | x |      
| Soil temperature level 4                                   | x | x | x | x |      
| Sea surface temperature                                    | | x | | |      
| Dew point temperature                                      | x | x | x | x |      
| Maximum temperature at 2 metres in the last 24 hours       | | x | | |      
| Minimum temperature at 2 metres in the last 24 hours       | | x | | |      
| **Mean sea level pressure**                                | x | x | | |      
| **Total precipitation**                                    | x | x | x | x |       
| Runoff                                                     | x | x | | |      
| Surface runoff                                             | x | | | |      
| Sub-surface runoff                                         | x | | | |      
| Evaporation                                                | x | x | x | x |      
| Potential evaporation                                      | x | | | |      
| Surface soil wetness at level 1                            | x | x | x | x |      
| Volumetric soil water layer 2                              | x | x | x | x |      
| Volumetric soil water layer 3                              | x | x | | |      
| Volumetric soil water layer 4                              | x | x | | |       
| Soil type                                                  | x | | | |      
| **10 metre U wind component**                              | x | x | x | x |       
| **10 metre V wind component**                              | x | x | x | x |       
| **Wind speed**                                             | | | x | x |      
| Instantaneous wind speed                                   | | x | | |      
| Eastward turbulent surface stress                          | | x | | |      
| Northward turbulent surface stress                         | | x | | |      
| Snow depth                                                 | x | x | x | x |      
| Snowfall accumulation                                      | x | x | | |      
| Snow density                                               | x | x | x | x |      
| Surface snow thickness                                     | x | x | x | x |      
| Total column snow water                                    | x | x | | |      
| Sea ice area fraction (ice cover)                          | | x | | |      
| Total cloud cover                                          | | x | | |      
| Latent heat flux                                           | | x | | |      
| Sensible heat flux                                         | | x | | |      
| Top net solar radiation                                    | | x | | |      
| Global radiation accumulation                              | | x | | |      
| Long wave radiation accumulation                           | | x | | |      
| Net long wave radiation accumulation                       | | x | | |      
| Net shortwave radiation accumulation                       | | x | | |      
| Net long wave radiation accumulation, top of the atmosphere| | x | | |      
| Low vegetation cover                                       | x | | | |      
| High vegetation cover                                      | x | | | |      
| Type of low vegetation cover                               | x | | | |      
| Type of high vegetation cover                              | x | | | |      
| Leaf area index                                            | x | | | |

# CAMS Variables 

| Available CAMS variables|CAMS| CAMSEU | CAMSEURA |
|:-----------------------------------------------------------|:----:|:-----:|:------:|
| Particulate matter d < 1 um / dust                | x | x | x |
| **Particulate matter d < 2.5 um**                 | x | x | x |
| **Particulate matter d < 10 um**                  | x | x | x |
| Total column Nitrogen dioxide                     | x | | |
| Total column Sulphur dioxide                      | x | | |
| Total column carbon monoxide                      | x | | |  
| Total column Formaldehyde                         | x | | |
| Total column hydrogen peroxide                    | x | | |
| Total column methane                              | x | | |
| Total column nitric acid                          | x | | |
| Total column peroxyacetyl nitrate                 | x | | |
| Total column isoprene                             | x  | | |
| Total column nitrogen monoxide                    | x | | |
| Total column hydroxyl radical                     | x | | |
| Total column ethane                               | x | | |
| Total column propane                              | x | | |
| GEMS Total column ozone                           | x | | |
| Total aerosol optical depth at 550 nm             | x | | |
| Sea salt aerosol optical depth at 550 nm          | x | | |
| Dust aerosol optical depth at 550 nm              | x | | | 
| Organic matter aerosol optical depth at 550 nm    | x | | |
| Black carbon aerosol optical depth at 550 nm      | | | | 
| Sulphate aerosol optical depth at 550 nm          | x | | | 
| Total aerosol optical depth at 469 nm             | x | | | 
| Total aerosol optical depth at 670 nm             | x | | | 
| Total aerosol optical depth at 865 nm             | x | | | 
| Total aerosol optical depth at 1240 nm            | x | | |
| UV biologically effective dose                    | x | | | 
| UV biologically effective dose clear-sky          | x | | |
|alder_pollen                                       | | x | |
|ammonia                                            | | x | x | 
|birch_pollen                                       | | x | | 
|carbon_monoxide                                    | | x | | 
|grass_pollen                                       | | x | | 
|mugwort_pollen                                     | | x | | 
|nitrogen_dioxide                                   | | x | x | 
|nitrogen_monoxide                                  | | x | x | 
|non_methane_vocs                                   | | x | x | 
|olive_pollen                                       | | x | | 
|ozone                                              | | x | x | 
|peroxyacyl_nitrates                                | | x | x | 
|ragweed_pollen                                     | | x | | 
|residential_elementary_carbon                      | | x | |
|secondary_inorganic_aerosol                        | | x | | 
|sulphur_dioxide                                    | | x | x |
|total_elementary_carbon                            | | x | | 
