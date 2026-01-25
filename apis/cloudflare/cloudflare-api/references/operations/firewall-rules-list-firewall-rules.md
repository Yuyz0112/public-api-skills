# GET /zones/{zone_id}/firewall/rules

**Resource:** [Firewall rules](../resources/Firewall-rules.md)
**List firewall rules**
**Operation ID:** `firewall-rules-list-firewall-rules`
⚠️ **Deprecated**

Fetches firewall rules in a zone. You can filter the results using several optional parameters.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | firewall_identifier | Yes |  |
| `description` | query | string | No |  |
| `action` | query | string | No |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |
| `id` | query | string | No |  |
| `paused` | query | boolean | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List firewall rules response |
| 4XX | List firewall rules response failure |

**Success Response Schema:**

[firewall_filter-rules-response-collection](../schemas/firewall/firewall-filter-rules-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
