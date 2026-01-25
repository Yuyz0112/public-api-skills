# POST /zones/{zone_id}/firewall/rules

**Resource:** [Firewall rules](../resources/Firewall-rules.md)
**Create firewall rules**
**Operation ID:** `firewall-rules-create-firewall-rules`
⚠️ **Deprecated**

Create one or more firewall rules.

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
| 200 | Create firewall rules response |
| 4XX | Create firewall rules response failure |

**Success Response Schema:**

[firewall_filter-rules-response-collection](../schemas/firewall/firewall-filter-rules-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
