# POST /zones/{zone_id}/page_shield/policies

**Resource:** [Page Shield](../resources/Page-Shield.md)
**Create a Page Shield policy**
**Operation ID:** `page-shield-create-policy`

Create a Page Shield policy.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | page-shield_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [page-shield_policy](../schemas/page-shield/page-shield-policy.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create a Page Shield policy response |
| 4XX | Create a Page Shield policy response failure |

**Success Response Schema:**

[page-shield_get-zone-policy-response](../schemas/page-shield/page-shield-get-zone-policy-response.md)

## Security

- **api_email**
- **api_key**
