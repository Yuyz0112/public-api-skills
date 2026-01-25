# PUT /zones/{zone_id}/firewall/rules

**Resource:** [Firewall rules](../resources/Firewall-rules.md)
**Update firewall rules**
**Operation ID:** `firewall-rules-update-firewall-rules`
⚠️ **Deprecated**

Updates one or more existing firewall rules.

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
| 200 | Update firewall rules response |
| 4XX | Update firewall rules response failure |

**Success Response Schema:**

[firewall_filter-rules-response-collection](../schemas/firewall/firewall-filter-rules-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
