# us-roofing-climate-data

Structured datasets (CSV/JSON) covering NOAA storm history, annual precipitation 
normals, and residential housing metrics across 109 US cities in 37 states.

Maintained by the [RidgeHero](https://ridgehero.com) engineering team to power 
localized weather-risk assessments for emergency roofing dispatch.

## Coverage

- 109 municipalities across 37 US states
- NOAA NWS county-level storm event history (wind, hail, tornado)
- Annual precipitation normals (30-year baseline)
- US Census residential housing density metrics

## Data Structure

Each city file is at `data/<state-abbr>/<city-slug>.json`:

```json
{
  "city": "Topeka",
  "state": "KS",
  "county": "Shawnee",
  "noaa_hail_events_5yr": 14,
  "noaa_wind_events_5yr": 31,
  "avg_annual_precip_in": 36.8,
  "housing_units": 62140,
  "median_year_built": 1968
}
```

## Related Resources

- [What To Do When Your Roof Is Leaking](https://ridgehero.com/guides/what-to-do-roof-leak/)
- [Emergency Roof Repair Network](https://ridgehero.com)
- [Contact & Dispatch](https://ridgehero.com/contact)

## License

Data is derived from public NOAA and US Census sources. See LICENSE.
