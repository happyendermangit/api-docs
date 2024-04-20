# Activities

`GET` /client/activities

Returns unreleased activites & released activities

## Response:

| Field | Type | Description|
|-------|------|------------|
| activities | Array of Activity Object | The list of the activities |
| applications | Array of Application Object | Application data for all of the activities |
| assets | Array of [Asset Object](#asset-object) | null | Assets data from activities |


## Asset Object:

| Field | Type | Description|
|-------|------|------------|
| id | snowflake | The id of the asset |
| type | number | The type of the asset |
| name | string | The file name of the asset |