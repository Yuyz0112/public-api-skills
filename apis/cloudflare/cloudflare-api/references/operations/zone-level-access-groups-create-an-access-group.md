# POST /zones/{zone_id}/access/groups

**Resource:** [Zone-Level Access groups](../resources/Zone-Level-Access-groups.md)
**Create an Access group**
**Operation ID:** `zone-level-access-groups-create-an-access-group`

Creates a new Access group.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Create an Access group response |
| 4XX | Create an Access group response failure |

**Success Response Schema:**

[access_groups_components-schemas-single_response-2](../schemas/access/access-groups-components-schemas-single-response-2.md)

## Security

- **api_email**
- **api_key**
