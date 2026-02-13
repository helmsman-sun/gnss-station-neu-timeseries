# gnss-station-neu-timeseries

Daily GNSS (NEU) displacement time series for 18 stations, 2009-01-02 to 2018-04-14, provided as CSV files for crustal deformation studies.  

## Repository structure
- `dataset/`: CSV time series files for each station (e.g., `G001neu9818.csv`)

## Time span
2009-01-02 to 2018-04-14 (daily records)

## CSV columns
Each CSV file contains:
- `time`: date (YYYY-MM-DD)
- `lon`, `lat`, `ver`: three-component displacement time series (horizontal components and vertical component; NEU or equivalent local components)
- `group`: station identifier
- `year`, `month`, `day`, `days`, `day_fraction`: helper fields for time-series processing

## Suggested citation
helmsman-sun (Year). *GNSS (NEU) displacement time series for 18 stations (2009–2018)* (Version v1.0.0) [Data set]. GitHub repository.

## License
CC BY 4.0 (recommended for data sharing).
