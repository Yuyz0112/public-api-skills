# GET /accounts/{account_id}/roles/{role_id}

**Resource:** [Account Roles](../resources/Account-Roles.md)
**Role Details**
**Operation ID:** `account-roles-role-details`

Get information about a specific role for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `role_id` | path | iam_role_components-schemas-identifier | Yes |  |
| `account_id` | path | iam_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Role Details response |
| 4XX | Role Details response failure |

**Success Response Schema:**

[iam_single_role_response](../schemas/iam/iam-single-role-response.md)

## Security

- **api_email**
- **api_key**
