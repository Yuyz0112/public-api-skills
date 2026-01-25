# GET /user/tokens/permission_groups

**Resource:** [User API Tokens](../resources/User-API-Tokens.md)
**List Token Permission Groups**
**Operation ID:** `permission-groups-list-permission-groups`

Find all available permission groups for API Tokens

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | query | string | No | Filter by the name of the permission group.
The value must be URL-encoded. |
| `scope` | query | string | No | Filter by the scope of the permission group.
The value must be URL-encoded. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Token Permission Groups response |
| 4XX | List Token Permission Groups response failure |

**Success Response Schema:**

[iam_permissions_group_response_collection](../schemas/iam/iam-permissions-group-response-collection.md)

## Security

- **api_token**
