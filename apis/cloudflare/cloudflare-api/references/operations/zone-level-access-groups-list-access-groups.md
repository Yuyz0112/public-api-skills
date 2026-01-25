# GET /zones/{zone_id}/access/groups

**Resource:** [Zone-Level Access groups](../resources/Zone-Level-Access-groups.md)
**List Access groups**
**Operation ID:** `zone-level-access-groups-list-access-groups`

Lists all Access groups.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Access groups response |
| 4XX | List Access groups response failure |

**Success Response Schema:**

[access_groups_components-schemas-response_collection](../schemas/access/access-groups-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
