# PUT /zones/{zone_id}/pagerules/{pagerule_id}

**Resource:** [Page Rules](../resources/Page-Rules.md)
**Update a Page Rule**
**Operation ID:** `page-rules-update-a-page-rule`

Replaces the configuration of an existing Page Rule. The configuration of the updated Page Rule will exactly match the data passed in the API request.

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
| 200 | Update a Page Rule response |
| 4XX | Update a Page Rule response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
