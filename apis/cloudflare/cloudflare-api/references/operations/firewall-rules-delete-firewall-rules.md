# DELETE /zones/{zone_id}/firewall/rules

**Resource:** [Firewall rules](../resources/Firewall-rules.md)
**Delete firewall rules**
**Operation ID:** `firewall-rules-delete-firewall-rules`
⚠️ **Deprecated**

Deletes existing firewall rules.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | firewall_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete firewall rules response |
| 4XX | Delete firewall rules response failure |

**Success Response Schema:**

[firewall_filter-rules-response-collection-delete](../schemas/firewall/firewall-filter-rules-response-collection-delete.md)

## Security

- **api_email**
- **api_key**
- **api_token**
