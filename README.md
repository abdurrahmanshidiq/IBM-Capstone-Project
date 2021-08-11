# COVID-19 Cases & Venue Analysis in South-Jakarta 

## Introduction to Business Problem
As a national capital of Indonesia, Jakarta considered as one of the most largest capital & busiest city in the world with over 10 million populations.  Jakarta is the heart of economic & business activities of the Indonesian archipelago. With these characteristics, Jakarta has many destination locations, e.g. office centers, business centers, shopping centers, residential areas, public space etc.
 During the COVID-19 pandemic, Jakarta has become the area with the most positive cases in Indonesia. The government requires to restrict or even close some places e.g. office, market, store, restaurant, etc. in order to reduce the transmission rate of the virus.
Restricting or even closing all the places, building, public places, etc. can suppress the infection of COVID-19 virus, but in other hand it will caused economic issue. The government should take the equilibrium between those two option. Before taking decision which venues should be restricted or closed, the questions are, Is there any relationship between type of venues/places and the number of positive case ?. if so, which type of  venues/places should be restricted / closed ? 

## Data Requirement
- South-Jakarta administrative data.From this data we need infromation about Districts & Regencies by scrapping wikipedia page using `bs4.beautifulsoup` package
- Foursquare API. Using this API we need information about list of venues in South-Jakarta including venue name, category and coordinate locations
- COVID-19 Data. We need number of positive cases in South-Jakarta
- Coordinate location data. Using `geopy` package to get coordinate location for each regency in South-Jakarta
- Geo JSON South-Jakarta. This data required for creating choropleth map

### Data Source
- [South Jakarta administrative area](https://id.wikipedia.org/wiki/Daftar_kecamatan_dan_kelurahan_di_Kota_Administrasi_Jakarta_Selatan)
- [Foursquare API](https://developer.foursquare.com/docs/api-reference/venues/explore/)
- [COVID-19 Data](https://data.jakarta.go.id/dataset/rekap-data-harian-covid-19-per-kelurahan-provinsi-dki-jakarta-bulan-november-2020)
- [South-Jakarta GeoJSON](https://github.com/thetrisatria/geojson-indonesia/blob/master/city-regency/id-jk-jaksel.geojson)
