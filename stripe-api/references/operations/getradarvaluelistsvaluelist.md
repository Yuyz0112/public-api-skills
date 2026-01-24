# GET /v1/radar/value_lists/{value_list}

**Resource:** [radar](../resources/radar.md)
**Retrieve a value list**
**Operation ID:** `GetRadarValueListsValueList`

<p>Retrieves a <code>ValueList</code> object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
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

