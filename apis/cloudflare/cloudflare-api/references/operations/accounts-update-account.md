# PUT /accounts/{account_id}

**Resource:** [Accounts](../resources/Accounts.md)
**Update Account**
**Operation ID:** `accounts-update-account`

Update an existing account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [iam_components-schemas-account](../schemas/iam/iam-components-schemas-account.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Account response |
| 4XX | Update Account response failure |

**Success Response Schema:**

[iam_response_single_account](../schemas/iam/iam-response-single-account.md)

## Security

- **api_email**
- **api_key**
