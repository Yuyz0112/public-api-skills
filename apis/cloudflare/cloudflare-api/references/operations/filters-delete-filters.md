# DELETE /zones/{zone_id}/filters

**Resource:** [Filters](../resources/Filters.md)
**Delete filters**
**Operation ID:** `filters-delete-filters`
⚠️ **Deprecated**

Deletes one or more existing filters.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | firewall_identifier | Yes |  |
| `id` | query | firewall_filters_components-schemas-id[] | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete filters response |
| 4XX | Delete filters response failure |

**Success Response Schema:**

[firewall_filter-delete-response-collection](../schemas/firewall/firewall-filter-delete-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
