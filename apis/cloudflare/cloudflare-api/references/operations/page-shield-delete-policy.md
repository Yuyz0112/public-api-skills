# DELETE /zones/{zone_id}/page_shield/policies/{policy_id}

**Resource:** [Page Shield](../resources/Page-Shield.md)
**Delete a Page Shield policy**
**Operation ID:** `page-shield-delete-policy`

Delete a Page Shield policy by ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | page-shield_id | Yes |  |
| `policy_id` | path | page-shield_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Delete a Page Shield policy response |
| 4XX | Delete a Page Shield policy response failure |

## Security

- **api_email**
- **api_key**
