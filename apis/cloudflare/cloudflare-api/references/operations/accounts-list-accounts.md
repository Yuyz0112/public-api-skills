# GET /accounts

**Resource:** [Accounts](../resources/Accounts.md)
**List Accounts**
**Operation ID:** `accounts-list-accounts`

List all accounts you have ownership or verified access to.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | query | string | No |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |
| `direction` | query | enum: asc, desc | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Accounts response |
| 4XX | List Accounts response failure |

**Success Response Schema:**

[iam_response_collection_accounts](../schemas/iam/iam-response-collection-accounts.md)

## Security

- **api_email**
- **api_key**
