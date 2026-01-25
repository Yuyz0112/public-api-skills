# POST /accounts/{account_id}/access/groups

**Resource:** [Access groups](../resources/Access-groups.md)
**Create an Access group**
**Operation ID:** `access-groups-create-an-access-group`

Creates a new Access group.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Create an Access group response |
| 4XX | Create an Access group response failure |

**Success Response Schema:**

[access_groups_components-schemas-single_response](../schemas/access/access-groups-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
