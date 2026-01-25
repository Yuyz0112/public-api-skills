# PUT /zones/{zone_id}/filters

**Resource:** [Filters](../resources/Filters.md)
**Update filters**
**Operation ID:** `filters-update-filters`
⚠️ **Deprecated**

Updates one or more existing filters.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | firewall_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** Array of [firewall_filter-rule-update-request](../schemas/firewall/firewall-filter-rule-update-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update filters response |
| 4XX | Update filters response failure |

**Success Response Schema:**

[firewall_filter-response-collection](../schemas/firewall/firewall-filter-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
