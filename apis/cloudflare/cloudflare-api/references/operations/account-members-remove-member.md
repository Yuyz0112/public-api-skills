# DELETE /accounts/{account_id}/members/{member_id}

**Resource:** [Account Members](../resources/Account-Members.md)
**Remove Member**
**Operation ID:** `account-members-remove-member`

Remove a member from an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `member_id` | path | iam_membership_components-schemas-identifier | Yes |  |
| `account_id` | path | iam_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Remove Member response |
| 4XX | Remove Member response failure |

**Success Response Schema:**

[iam_api-response-single-id](../schemas/iam/iam-api-response-single-id.md)

## Security

- **api_email**
- **api_key**
