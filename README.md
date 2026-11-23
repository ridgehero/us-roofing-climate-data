# RidgeHero: US Municipal Roofing & Storm Data

Open-source reference datasets, NOAA severe weather frequency records, and residential roof triage documentation maintained by the RidgeHero research project.

**Project Website:** [RidgeHero Roofing Network](https://ridgehero.com)

---

## Overview

This repository standardizes local meteorological stress metrics and residential housing age data across 109 US municipalities. The dataset correlates National Weather Service (NWS) storm records (hail, high-wind derechoes, severe thunderstorms) with residential roof maintenance lifecycles.

### Data Coverage
* **Municipalities Tracked**: 109 cities across 37 US states
* **Historical Range**: 1996–present (NOAA Storm Events Database)
* **Key Indicators**: Median housing build year, single-family structure ratios, annual precipitation normals, wettest month indicators, and recorded hail/wind event counts.

---

## Published Documentation & Guides

Technical guides and triage protocols developed for the dataset:
* [Emergency Roof Leak Response Protocol](https://ridgehero.com/guides/what-to-do-roof-leak/)
* [Severe Weather & Hail Damage Identification](https://ridgehero.com/guides/storm-damage-basics/)
* [Contractor License & Insurance Verification Standards](https://ridgehero.com/guides/verify-roofing-contractor/)
* [US Municipal Service Directory (109 Cities)](https://ridgehero.com/#cities)

---

## Data Structure Example

```json
{
  "city": "Topeka",
  "state": "Kansas",
  "county": "Shawnee",
  "climate": {
    "annual_precipitation_in": 37,
    "wettest_month": "May",
    "severe_events_since_1996": 1066,
    "primary_hazard": "Hail (452 events)"
  },
  "housing": {
    "median_year_built": 1967,
    "single_family_ratio": "63.9%"
  }
}
```

---

## License & Attribution

Data compiled from US Census Bureau (ACS 5-Year Estimates) and the National Oceanic and Atmospheric Administration (NOAA). Published for public reference and homeowner education under open documentation standards.

## Maintainer & Inquiries

Maintained by [@ridgehero](https://github.com/ridgehero).  
* **Emergency Dispatch:** (855) 513-0946  
* **General:** [Contact RidgeHero](https://ridgehero.com/contact)
