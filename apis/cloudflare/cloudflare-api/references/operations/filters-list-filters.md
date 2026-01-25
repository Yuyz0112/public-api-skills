# GET /zones/{zone_id}/filters

**Resource:** [Filters](../resources/Filters.md)
**List filters**
**Operation ID:** `filters-list-filters`
⚠️ **Deprecated**

Fetches filters in a zone. You can filter the results using several optional parameters.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | firewall_identifier | Yes |  |
| `paused` | query | any | No |  |
| `expression` | query | string | No |  |
| `description` | query | string | No |  |
| `ref` | query | string | No |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |
| `id` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List filters response |
| 4XX | List filters response failure |

**Success Response Schema:**

[firewall_filter-response-collection](../schemas/firewall/firewall-filter-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
