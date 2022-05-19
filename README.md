# SmartMet-server for Harmonia project 

SmartMet Server is a data and product server which provides acces to both observation and forecast data. It is used for data services and product generation. Smartmet Server can read input from various sources and it provides several ouput interfaces and formats. For more detailed description, see the [SmartMet Server wiki pages](https://github.com/fmidev/smartmet-server/wiki).

SmartMet Server purpose is a service to make data available directly to web apps without needing any data downloading and processing steps on a server. You can directly write javascript web apps to use Copernicus data for the Harmonia project. To get a feel for the data offered https://harmonia.geoss.space/grid-gui is a general data browser. This service has datasets from several producers (f.ex. currently working: ERA5, ECSF, ECB2SF, ECBSF). ECSF, ECB2SF and ECBSF seasonal forecasts are available once per month for 215 daily forecasts 7 months ahead. ERA5 is every day the reanalysis from 5 days ago. To utilize datasets shown on this service, the SmartMet Server TimeSeries plugin can be used.

For example web app code using a smartmet-server check out the https://github.com/fmidev/harvesterseasons-site repository and check out the service https://harvesterseasons.com.

# Using the Timeseries API for data in table format

The TimeSeries plugin can be used to fetch time series information for observation and forecast data, with specific time or time interval chosen by the user. The datasets can be downloaded with a HTTP request which contains the parameters needed to obtain the information, processing the results and formatting the output.

