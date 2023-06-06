# twenty-mph-streets

With Sammy's Law up for consideration in this legislative session, I identified the streets where we should consider lowering the speed limit from 25 to 20 mph. The resulting map includes the top 50 streets for number of collisions caused by unsafe speed per mile.

The output of this repository is a leaflet interactive map with the 50 streets highlighted and popups showing crash data.

## Technical Notes:
Data on collisions - https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95
Data on speed limits - https://data.cityofnewyork.us/Transportation/VZV_Speed-Limits/7n5j-865y
Borough boundaries - https://data.cityofnewyork.us/City-Government/Borough-Boundaries/tqmj-j8zm

Streets in the top 50 have to have at least 35 crashes since 2019, be beyond a minimum length, and be primarily 25mph speed limits (70% or more of the street length is 25mph)

Not all street crashes could be assigned to the correct street in the speed limit data due to data constraints. Many collisions are missing location data, or have various street name data entry errors. I've cleaned up some obvious errors but this does not reflect the full universe of crashes as not all could be matched. As a result, these numbers may undercount the number of collisions on a given street.

Data on crash reason is sometimes unreliable, missing, or "unspecified". With better data this list could be improved.
