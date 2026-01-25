# GET /zones/{zone_id}/firewall/lockdowns

**Resource:** [Zone Lockdown](../resources/Zone-Lockdown.md)
**List Zone Lockdown rules**
**Operation ID:** `zone-lockdown-list-zone-lockdown-rules`

Fetches Zone Lockdown rules. You can filter the results using several optional parameters.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | firewall_identifier | Yes |  |
| `page` | query | number | No |  |
| `description` | query | any | No |  |
| `modified_on` | query | any | No |  |
| `ip` | query | any | No |  |
| `priority` | query | any | No |  |
| `uri_search` | query | any | No |  |
| `ip_range_search` | query | any | No |  |
| `per_page` | query | number | No |  |
| `created_on` | query | string (date-time) | No |  |
| `description_search` | query | string | No |  |
| `ip_search` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Zone Lockdown rules response |
| 4XX | List Zone Lockdown rules response failure |

**Success Response Schema:**

[firewall_zonelockdown_response_collection](../schemas/firewall/firewall-zonelockdown-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
