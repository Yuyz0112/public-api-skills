# PATCH /zones/{zone_id}/firewall/rules

**Resource:** [Firewall rules](../resources/Firewall-rules.md)
**Update priority of firewall rules**
**Operation ID:** `firewall-rules-update-priority-of-firewall-rules`
⚠️ **Deprecated**

Updates the priority of existing firewall rules.

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
| 200 | Update priority of firewall rules response |
| 4XX | Update priority of firewall rules response failure |

**Success Response Schema:**

[firewall_filter-rules-response-collection](../schemas/firewall/firewall-filter-rules-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
