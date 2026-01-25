# POST /accounts/{account_id}/members

**Resource:** [Account Members](../resources/Account-Members.md)
**Add Member**
**Operation ID:** `account-members-add-member`

Add a user to the list of members for this account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Add Member response |
| 4XX | Add Member response failure |

**Success Response Schema:**

[iam_single_member_response_with_policies](../schemas/iam/iam-single-member-response-with-policies.md)

## Security

- **api_email**
- **api_key**
