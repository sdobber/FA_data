# FA_data

Example datasets for [FluxArchitectures](https://github.com/sdobber/FluxArchitectures).

The following data from https://github.com/laiguokun/multivariate-time-series-data is included:

* `solar.bson`: The raw data is coming from http://www.nrel.gov/grid/solar-power-data.html: It contains the solar power production records in the year of 2006, which is sampled every 10 minutes from 137 PV plants in Alabama State.

* `traffic.bson`: The raw data is coming from http://pems.dot.ca.gov. The data in this repo is a collection of 48 months (2015-2016) hourly data from the California Department of Transportation. The data describes the road occupancy rates (between 0 and 1) measured by different sensors on San Francisco Bay area freeways.

* `electricity.bson`: The raw dataset is from https://archive.ics.uci.edu/ml/datasets/ElectricityLoadDiagrams20112014. It is the electricity consumption in kWh was recorded every 15 minutes from 2011 to 2014 for 321 clients. The data has been cleaned and converted to hourly consumption.

* `exchange_rate.bson`: The collection of daily exchange rates of eight foreign countries including Australia, Great Britain, Canada, Switzerland, China, Japan, New Zealand and Singapore ranging from 1990 to 2016.

Use the `BSON.jl` package for loading the files.