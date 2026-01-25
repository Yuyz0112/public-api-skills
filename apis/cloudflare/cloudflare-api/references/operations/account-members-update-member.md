# PUT /accounts/{account_id}/members/{member_id}

**Resource:** [Account Members](../resources/Account-Members.md)
**Update Member**
**Operation ID:** `account-members-update-member`

Modify an account member.

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
| 200 | Update Member response |
| 4XX | Update Member response failure |

**Success Response Schema:**

[iam_single_member_response_with_policies](../schemas/iam/iam-single-member-response-with-policies.md)

## Security

- **api_email**
- **api_key**
