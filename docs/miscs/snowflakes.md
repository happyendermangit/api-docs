---
sidebar_position: 1
---

# Snowflake

**``GET``** `/misc/snowflake`

Returns the data of a snowflake given or a new generated snowflake

## Url query Params:

| Field | Type | Description|
|-------|------|------------|
| snowflake | string \| undefined | The snowflake you want to check (dont add it if you want to generate a snowflake) |


## Response:

| Field | Type | Description|
|-------|------|------------|
| snowflake | string | The inputed/generated snowflake |
| date | string | The date when the snowflake was generated |
| detected_from_input | boolean | Weather the date was detected from the inputted snowflake or from a generated snowflake |