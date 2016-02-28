# Faraday Places

[Faraday](http://faraday.io)'s gazetter

[Blog post](http://blog.faraday.io/faraday-places-our-simple-gazetteer/)

## Sample

| id | name | type |
|----|------|------|
|205585|Bear Creek, AK|cdp|
|77767492|67492|zcta|
|4211932952|Hartley, PA|town|
|4843144|Llano, TX|city|

## Columns


### id
Census-assigned [`GeoID`](https://www.census.gov/geo/reference/geoidentifiers.html) of the Place. ZCTA IDs have been assigned `777{5-digit zipcode}` to avoid conflict with other 5-character GeoIDs.

### name
Commonly-accepted name of the Place. (Zipcodes are represented as strings to maintain initial zeroes.)

### type
The Place's type. Types include `borough`, `cdp`, `city`, `county`, `metro`, `micro`, `state`, `town`, `village`, and `zcta`.


## Download

[Latest CSV (zipped)](https://github.com/faradayio/places/archive/master.zip)

## Suggestions? Issues?

Please [open an issue](https://github.com/faradayio/places/issues/new) or fork, fix, and submit a pull request.
