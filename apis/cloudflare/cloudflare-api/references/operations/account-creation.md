# POST /accounts

**Resource:** [Accounts](../resources/Accounts.md)
**Create an account**
**Operation ID:** `account-creation`

Create an account (only available for tenant admins at this time)

## Request Body

Parameters for account creation

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [iam_create-account](../schemas/iam/iam-create-account.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Account Creation Success Response |
| 4XX | Account Creation Failure Response |

**Success Response Schema:**

[iam_response_single_account](../schemas/iam/iam-response-single-account.md)

## Security

- **api_email**
- **api_key**
