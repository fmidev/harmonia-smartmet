# Datasets from Copernicus for the Harmonia project 

https://harmonia.geoss.space/grid-gui

| Parameter         | Parameter name | ERA5 | ECSF | ECBSF | ECB2SF |
|:------------------|:---------------|:-----|:-----|-------|--------|
|CVH-N [0 to 1]     |High vegetation cover||
|CVL-N [O to 1]     |Low vegetation cover||
|EVAP-M [m]         |Evaporation (m of water equivalent)||
|EVAPP-M [m]        |Potential evaporation|EVAP-MM [mm]|
|LAI_HV-M2M2 [m²/m²]|Leaf area index high vegetation||
|LAI_LV-M2M2 [m²/m²]|Leaf area index low vegetation||
|PSEA-PA [Pa]       |Pressure reduced to mean sea level|PSEA-HPA [hPa]|
|RO-M [m]|Runoff in depth of water in meters||
|RR-M [m]|Total precipitation in meters|RR-MM [mm]|
|SD-M [m]|Snow depth in meters||
|SNACC-KGM2 [kg/m²]|Snowfall accumulation in mm||
|SND-KGM3 [kg/m³]|Snow density in kg/m3||
|SOILTY-N|Soil type||
|SRO-M [m]|Surface runoff (metres)||
|SSRO-M [m]|Subsurface runoff (metres)||
|STL1-K [K]|Soil temperature level 1 in Kelvins|STL1-C [C]|
|STL2-K [K]|Soil temperature level 2 in Kelvins|STL2-C [C]|
|STL3-K [K]|Soil temperature level 3 in Kelvins|STL3-C [C]|
|STL4-K [K]|Soil temperature level 4 in Kelvins|STL4-C [C]|
|SWVL1-M3M3 [m³/m³]|Volumetric soil water layer 1||
|SWVL2-M3M3 [m³/m³]|Volumetric soil water layer 2||
|SWVL3-M3M3 [m³/m³]|Volumetric soil water layer 3||
|SWVL4-M3M3 [m³/m³]|Volumetric soil water layer 4||
|TAS-K [K]|2 metre temperature in Kelvins|TAS-C [C]|
|TCSW-KGM2 [kg/m²]|Total column snow water (kg m-2)||
|TD-K [K]|Dew point temperature in K|TD-C [C]|
|TVH-N|Type of high vegetation||
|TVL-N|Type of low vegetation||
|U10-MS [m/s]|10 metre U wind component||
|V10-MS [m/s]|10 metre V wind component||
|WESD-M [m]|Snow depth (m of water equivalent)||


## ERA5L

## ECSF, ECBSF, ECB2SF 

## S3SY


# C3S Variables   

Bolded variables are assumed to be of most interest to HARMONIA project based on WP2.1 Workshop Report and other. 

| Available C3S variables|ERA5/CERRA|ECSF|ECBSF|climate prediction| 
|:-----------------------------------------------------------|:---:|:----:|:-----:|:------:|
| **Air temperature (2 m)**                                  | x | x | x | x |
| **Soil temperature level 1 (ground temperature)**          | x | x | x |  |      
| Soil temperature level 2                                   | x | x | x |  |      
| Soil temperature level 3                                   | x | x | x |  |      
| Soil temperature level 4                                   | x | x | x |  |      
| Sea surface temperature                                    | | x | | |      
| Dew point temperature                                      | x | x | x | |      
| Maximum temperature at 2 metres in the last 24 hours       | | x | | |      
| Minimum temperature at 2 metres in the last 24 hours       | | x | | |      
| **Mean sea level pressure**                                | x | x | | |      
| **Total precipitation**                                    | x | x | x | x |       
| Runoff                                                     | x | x | | |      
| Surface runoff                                             | x | | | |      
| Sub-surface runoff                                         | x | | | |      
| Evaporation                                                | x | x | x |  |      
| Potential evaporation                                      | x | | | |      
| Surface soil wetness at level 1                            | x | x | x |  |      
| Volumetric soil water layer 2                              | x | x | x |  |      
| Volumetric soil water layer 3                              | x | x | | |      
| Volumetric soil water layer 4                              | x | x | | |       
| Soil type                                                  | x | | | |      
| **10 metre U wind component**                              | x | x | x | x |       
| **10 metre V wind component**                              | x | x | x | x |       
| **Wind speed**                                             | | | x | x |      
| Instantaneous wind speed                                   | | x | x | |      
| Eastward turbulent surface stress                          | | x | | |      
| Northward turbulent surface stress                         | | x | | |      
| Snow depth                                                 | x | x | x |  |      
| Snowfall accumulation                                      | x | x | | |      
| Snow density                                               | x | x | x |  |      
| Surface snow thickness                                     | x | x | x |  |      
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
| Net long wave rad. acc, top of atmosphere                  | | x | | |      
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
