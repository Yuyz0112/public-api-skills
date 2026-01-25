# PATCH /zones/{zone_id}/pagerules/{pagerule_id}

**Resource:** [Page Rules](../resources/Page-Rules.md)
**Edit a Page Rule**
**Operation ID:** `page-rules-edit-a-page-rule`

Updates one or more fields of an existing Page Rule.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `pagerule_id` | path | zones_schemas-identifier | Yes |  |
| `zone_id` | path | zones_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Edit a Page Rule response |
| 4XX | Edit a Page Rule response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
