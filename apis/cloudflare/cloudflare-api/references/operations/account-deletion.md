# DELETE /accounts/{account_id}

**Resource:** [Accounts](../resources/Accounts.md)
**Delete a specific account**
**Operation ID:** `account-deletion`

Delete a specific account (only available for tenant admins at this time). This is a permanent operation that will delete any zones or other resources under the account

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Account Deletion Success Response |
| 4XX | Account Deletion Failure Response |

**Success Response Schema:**

[iam_api-response-single-id](../schemas/iam/iam-api-response-single-id.md)

## Security

- **api_email**
- **api_key**
