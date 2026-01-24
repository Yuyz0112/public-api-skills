# POST /v1/radar/value_lists/{value_list}

**Resource:** [radar](../resources/radar.md)
**Update a value list**
**Operation ID:** `PostRadarValueListsValueList`

<p>Updates a <code>ValueList</code> object by setting the values of the parameters passed. Any parameters not provided will be left unchanged. Note that <code>item_type</code> is immutable.</p>

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

[radar.value_list](../schemas/radar-value/radar-value-list.md)

