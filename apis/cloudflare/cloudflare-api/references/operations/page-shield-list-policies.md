# GET /zones/{zone_id}/page_shield/policies

**Resource:** [Page Shield](../resources/Page-Shield.md)
**List Page Shield policies**
**Operation ID:** `page-shield-list-policies`

Lists all Page Shield policies.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | page-shield_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Page Shield policies response |
| 4XX | List Page Shield policies response failure |

**Success Response Schema:**

[page-shield_list-zone-policies-response](../schemas/page-shield/page-shield-list-zone-policies-response.md)

## Security

- **api_email**
- **api_key**
