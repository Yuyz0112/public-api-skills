# GET /accounts/{account_id}

**Resource:** [Accounts](../resources/Accounts.md)
**Account Details**
**Operation ID:** `accounts-account-details`

Get information about a specific account that you are a member of.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Account Details response |
| 4XX | Account Details response failure |

**Success Response Schema:**

[iam_response_single_account](../schemas/iam/iam-response-single-account.md)

## Security

- **api_email**
- **api_key**
