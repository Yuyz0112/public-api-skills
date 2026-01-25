# GET /v1/radar/value_list_items/{item}

**Resource:** [radar](../resources/radar.md)
**Retrieve a value list item**
**Operation ID:** `GetRadarValueListItemsItem`

<p>Retrieves a <code>ValueListItem</code> object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `item` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[radar.value_list_item](../schemas/radar-value/radar-value-list-item.md)

