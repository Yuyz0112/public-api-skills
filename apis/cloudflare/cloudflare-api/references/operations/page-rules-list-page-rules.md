# GET /zones/{zone_id}/pagerules

**Resource:** [Page Rules](../resources/Page-Rules.md)
**List Page Rules**
**Operation ID:** `page-rules-list-page-rules`

Fetches Page Rules in a zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | zones_schemas-identifier | Yes |  |
| `order` | query | enum: status, priority | No |  |
| `direction` | query | enum: asc, desc | No |  |
| `match` | query | enum: any, all | No |  |
| `status` | query | enum: active, disabled | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Page Rules response |
| 4XX | List Page Rules response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
