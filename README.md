# JSON-timezones
Different JSON representations for timezone data

### AllTimezones.json: an array of all global timezones with no country.
  E.g `[ "Abidjan", ... ]`

### KeyedTimezones.json: an object with countries as keys, and an array of timezones each value.
  E.g `{ "Africa": [ "Abidjan", ... ] }`

### TimezonesWithCountry.json: an array of all global timezones prefixed with country
  E.g `[ "Africa/Abidjan", ... ]`
