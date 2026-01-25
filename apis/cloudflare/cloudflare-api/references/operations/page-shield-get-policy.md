# GET /zones/{zone_id}/page_shield/policies/{policy_id}

**Resource:** [Page Shield](../resources/Page-Shield.md)
**Get a Page Shield policy**
**Operation ID:** `page-shield-get-policy`

Fetches a Page Shield policy by ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | page-shield_id | Yes |  |
| `policy_id` | path | page-shield_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a Page Shield policy response |
| 4XX | Get a Page Shield policy response failure |

**Success Response Schema:**

[page-shield_get-zone-policy-response](../schemas/page-shield/page-shield-get-zone-policy-response.md)

## Security

- **api_email**
- **api_key**
