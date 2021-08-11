# COVID-19 Cases & Venue Analysis in South-Jakarta 

## Introduction

# Data Requirement
- South-Jakarta administrative data.From this data we need infromation about Districts & Regencies by scrapping wikipedia page using `beautifulsoup` package
- Foursquare API. Using this API we need information about list of venues in South-Jakarta including venue name, category and coordinate locations
- COVID-19 Data. We need number of positive cases in South-Jakarta
- Coordinate location data. Using `geopy` package to get coordinate location for each regency in South-Jakarta
- Geo JSON South-Jakarta. This data required for creating choropleth map

## Data Source
- [South Jakarta administrative area](https://id.wikipedia.org/wiki/Daftar_kecamatan_dan_kelurahan_di_Kota_Administrasi_Jakarta_Selatan)
- [Foursquare API](https://developer.foursquare.com/docs/api-reference/venues/explore/)
- [COVID-19 Data](https://data.jakarta.go.id/dataset/rekap-data-harian-covid-19-per-kelurahan-provinsi-dki-jakarta-bulan-november-2020)
- [South-Jakarta GeoJSON](https://github.com/thetrisatria/geojson-indonesia/blob/master/city-regency/id-jk-jaksel.geojson)
