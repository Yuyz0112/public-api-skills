# GET /zones/{zone_id}/access/groups/{group_id}

**Resource:** [Zone-Level Access groups](../resources/Zone-Level-Access-groups.md)
**Get an Access group**
**Operation ID:** `zone-level-access-groups-get-an-access-group`

Fetches a single Access group.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `group_id` | path | access_uuid | Yes |  |
| `zone_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get an Access group response |
| 4XX | Get an Access group response failure |

**Success Response Schema:**

[access_groups_components-schemas-single_response-2](../schemas/access/access-groups-components-schemas-single-response-2.md)

## Security

- **api_email**
- **api_key**
