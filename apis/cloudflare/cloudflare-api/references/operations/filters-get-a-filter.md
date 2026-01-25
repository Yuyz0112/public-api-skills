# GET /zones/{zone_id}/filters/{filter_id}

**Resource:** [Filters](../resources/Filters.md)
**Get a filter**
**Operation ID:** `filters-get-a-filter`
⚠️ **Deprecated**

Fetches the details of a filter.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `filter_id` | path | firewall_filters_components-schemas-id | Yes |  |
| `zone_id` | path | firewall_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a filter response |
| 4XX | Get a filter response failure |

**Success Response Schema:**

[firewall_filter-response-single](../schemas/firewall/firewall-filter-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
