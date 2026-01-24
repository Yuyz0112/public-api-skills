# DELETE /v1/radar/value_lists/{value_list}

**Resource:** [radar](../resources/radar.md)
**Delete a value list**
**Operation ID:** `DeleteRadarValueListsValueList`

<p>Deletes a <code>ValueList</code> object, also deleting any items contained within the value list. To be deleted, a value list must not be referenced in any rules.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `value_list` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[deleted_radar.value_list](../schemas/deleted/deleted-radar-value-list.md)

