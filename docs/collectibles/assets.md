# Assets

`GET` `/collectibles/assets`

Returns assets of collectibles application

## Response:

Array of [Asset Object](#asset-object)

## Asset Object:

| Field | Type | Description|
|-------|------|------------|
| id | snowflake | The id of the asset |
| type | number | The type of the asset |
| name | string | The file name of the asset |

:::info[Note:]
All assets are hosted under this url: `https://cdn.discordapp.com/app-assets/1096190356233670716/:asset_id.png?size=4096`
:::
