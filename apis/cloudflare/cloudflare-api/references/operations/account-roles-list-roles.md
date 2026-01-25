# GET /accounts/{account_id}/roles

**Resource:** [Account Roles](../resources/Account-Roles.md)
**List Roles**
**Operation ID:** `account-roles-list-roles`

Get all available roles for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Roles response |
| 4XX | List Roles response failure |

**Success Response Schema:**

[iam_collection_role_response](../schemas/iam/iam-collection-role-response.md)

## Security

- **api_email**
- **api_key**
