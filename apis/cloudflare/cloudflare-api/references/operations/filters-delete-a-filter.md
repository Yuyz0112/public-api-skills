# DELETE /zones/{zone_id}/filters/{filter_id}

**Resource:** [Filters](../resources/Filters.md)
**Delete a filter**
**Operation ID:** `filters-delete-a-filter`
⚠️ **Deprecated**

Deletes an existing filter.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `filter_id` | path | firewall_filters_components-schemas-id | Yes |  |
| `zone_id` | path | firewall_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete a filter response |
| 4XX | Delete a filter response failure |

**Success Response Schema:**

[firewall_filter-delete-response-single](../schemas/firewall/firewall-filter-delete-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
