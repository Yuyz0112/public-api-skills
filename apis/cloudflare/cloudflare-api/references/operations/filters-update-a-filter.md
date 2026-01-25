# PUT /zones/{zone_id}/filters/{filter_id}

**Resource:** [Filters](../resources/Filters.md)
**Update a filter**
**Operation ID:** `filters-update-a-filter`
⚠️ **Deprecated**

Updates an existing filter.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `filter_id` | path | firewall_filters_components-schemas-id | Yes |  |
| `zone_id` | path | firewall_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [firewall_filter](../schemas/firewall/firewall-filter.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update a filter response |
| 4XX | Update a filter response failure |

**Success Response Schema:**

[firewall_filter-response-single](../schemas/firewall/firewall-filter-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
