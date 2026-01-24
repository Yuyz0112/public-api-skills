# DELETE /v1/radar/value_list_items/{item}

**Resource:** [radar](../resources/radar.md)
**Delete a value list item**
**Operation ID:** `DeleteRadarValueListItemsItem`

<p>Deletes a <code>ValueListItem</code> object, removing it from its parent value list.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `item` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[deleted_radar.value_list_item](../schemas/deleted/deleted-radar-value-list-item.md)

