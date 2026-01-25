# PUT /accounts/{account_id}/access/groups/{group_id}

**Resource:** [Access groups](../resources/Access-groups.md)
**Update an Access group**
**Operation ID:** `access-groups-update-an-access-group`

Updates a configured Access group.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `group_id` | path | access_uuid | Yes |  |
| `account_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update an Access group response |
| 4XX | Update an Access group response failure |

**Success Response Schema:**

[access_groups_components-schemas-single_response](../schemas/access/access-groups-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
