# POST /v1/radar/value_lists

**Resource:** [radar](../resources/radar.md)
**Create a value list**
**Operation ID:** `PostRadarValueLists`

<p>Creates a new <code>ValueList</code> object, which can then be referenced in rules.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[radar.value_list](../schemas/radar-value/radar-value-list.md)

