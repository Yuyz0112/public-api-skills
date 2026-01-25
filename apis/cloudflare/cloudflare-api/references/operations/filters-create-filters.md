# POST /zones/{zone_id}/filters

**Resource:** [Filters](../resources/Filters.md)
**Create filters**
**Operation ID:** `filters-create-filters`
⚠️ **Deprecated**

Creates one or more filters.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | firewall_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** Array of [firewall_filter](../schemas/firewall/firewall-filter.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create filters response |
| 4XX | Create filters response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
