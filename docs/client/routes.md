# Routes

`GET` /client/routes

Returns discord api routes used on the client with their allowed methods (if found)

## Response:

Object with values of [Route Object](#route-object)

## Route Object:

| Field | Type | Description|
|-------|------|------------|
| url | string | The url of the route |
| allowed_methods | Array of methods or null | The allowed methods for this route (if found) |
