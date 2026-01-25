# GET /zones/{zone_id}/settings/zaraz/history

**Resource:** [Zaraz](../resources/Zaraz.md)
**List Zaraz historical configuration records**
**Operation ID:** `get-zones-zone_identifier-zaraz-history`

Lists a history of published Zaraz configuration records for a zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | zaraz_identifier | Yes |  |
| `offset` | query | integer | No | Ordinal number to start listing the results with. Default value is 0. |
| `limit` | query | integer | No | Maximum amount of results to list. Default value is 10. |
| `sortField` | query | enum: id, user_id, description... | No | The field to sort by. Default is updated_at. |
| `sortOrder` | query | enum: DESC, ASC | No | Sorting order. Default is DESC. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Zaraz historical configuration records response |
| 4XX | List Zaraz historical configuration records failure |

**Success Response Schema:**

[zaraz_zaraz-history-response](../schemas/zaraz/zaraz-zaraz-history-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
