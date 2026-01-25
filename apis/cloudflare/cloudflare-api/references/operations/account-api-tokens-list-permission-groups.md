# GET /accounts/{account_id}/tokens/permission_groups

**Resource:** [Account Owned API Tokens](../resources/Account-Owned-API-Tokens.md)
**List Permission Groups**
**Operation ID:** `account-api-tokens-list-permission-groups`

Find all available permission groups for Account Owned API Tokens

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |
| `name` | query | string | No | Filter by the name of the permission group.
The value must be URL-encoded. |
| `scope` | query | string | No | Filter by the scope of the permission group.
The value must be URL-encoded. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Account Owned API Token Permission Groups response |
| 4XX | List Account Owned API Token Permission Groups response failure |

**Success Response Schema:**

[iam_permissions_group_response_collection](../schemas/iam/iam-permissions-group-response-collection.md)

## Security

- **api_token**
