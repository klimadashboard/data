# Geosphere Datasets from Austrian weather stations

To track changes in temperature, snowfall and more, we use historic data provided by Geosphere (formally known as ZAMG) [on their data hub](https://data.hub.zamg.ac.at).
For more information on their API, [see their documentation](https://dataset.api.hub.zamg.ac.at/v1/docs/).

Our datasets are automatically updated every morning between 7am and 9am.

## Stations
For our visualisations, we only work with a subset of ZAMG weather stations, which have
- recorded data since at least 1960
- no major reporting gaps in that time period

Each stations’s data can be found in /stations/ in a subfolder labelled by the ID of the station (see stations.csv for reference). Station ID 105 is Wien/Hohe Warte, the oldest weather station in Austria.
For each station, we’ve got...
- data.json with the raw data exported from the API
- monthly.csv, with data for temperature and temperature days by months
- yearly.csv, same as above but aggregated by year
- yearly-today.csv, track temperature days until the current day in the year, going back in time (so on January 31st, data for every year until the last day of January in that year will be calculated)