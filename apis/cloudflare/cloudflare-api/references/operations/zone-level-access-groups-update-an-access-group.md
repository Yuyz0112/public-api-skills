# PUT /zones/{zone_id}/access/groups/{group_id}

**Resource:** [Zone-Level Access groups](../resources/Zone-Level-Access-groups.md)
**Update an Access group**
**Operation ID:** `zone-level-access-groups-update-an-access-group`

Updates a configured Access group.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `group_id` | path | access_uuid | Yes |  |
| `zone_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update an Access group response |
| 4XX | Update an Access group response failure |

**Success Response Schema:**

[access_groups_components-schemas-single_response-2](../schemas/access/access-groups-components-schemas-single-response-2.md)

## Security

- **api_email**
- **api_key**
