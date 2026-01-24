# POST /v1/radar/value_list_items

**Resource:** [radar](../resources/radar.md)
**Create a value list item**
**Operation ID:** `PostRadarValueListItems`

<p>Creates a new <code>ValueListItem</code> object, which is added to the specified parent value list.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[radar.value_list_item](../schemas/radar-value/radar-value-list-item.md)

