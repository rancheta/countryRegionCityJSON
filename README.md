# countryRegionCityJSON
JSON files of all the world's cities with populations above 1000 people. Derived from the GeoNames geographical database, good for liteweight geographic applications. If you need more flexibility you may want to look into loading the data into a database like https://github.com/colemanm/gazetteer/blob/master/docs/geonames_postgis_import.md.

### city_json
contains main files of which the others are derived

containing a list of country data in countries.json
containing a list of cities over a certain population in citiesOverPop______.json

### region_json
Contains files with a country_data object and a list of the regions in the area and data about them

### region_city_data
contains folders of countries, within them are a series of files for the regions in the country

### country_city_data
contains a country_data object containing country information 
contains a cities array with a list of cities and city data in the said country 

Each region file contains a region_data object, country_data object, and a list of cities within said region
