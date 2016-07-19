# city_county_map
Data (and maybe code) supporting mapping City/State info to county

We've attempted to map a given City,State pairing to a unique County,State pairing

## Multiple Counties
For cities (or other entities) that span multiple counties, the following logic was used
1. If Wikipedia lists it as "mostly in county X", that is the assigned county
2. If the entity is the county seat of only one of the counties it spans, it is assigned to that county
