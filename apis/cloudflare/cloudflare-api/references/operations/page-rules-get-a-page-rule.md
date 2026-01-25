# GET /zones/{zone_id}/pagerules/{pagerule_id}

**Resource:** [Page Rules](../resources/Page-Rules.md)
**Get a Page Rule**
**Operation ID:** `page-rules-get-a-page-rule`

Fetches the details of a Page Rule.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `pagerule_id` | path | zones_schemas-identifier | Yes |  |
| `zone_id` | path | zones_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a Page Rule response |
| 4XX | Get a Page Rule response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
