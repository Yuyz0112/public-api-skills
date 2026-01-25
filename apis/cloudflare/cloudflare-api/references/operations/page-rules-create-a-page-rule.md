# POST /zones/{zone_id}/pagerules

**Resource:** [Page Rules](../resources/Page-Rules.md)
**Create a Page Rule**
**Operation ID:** `page-rules-create-a-page-rule`

Creates a new Page Rule.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | zones_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create a Page Rule response |
| 4XX | Create a Page Rule response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
