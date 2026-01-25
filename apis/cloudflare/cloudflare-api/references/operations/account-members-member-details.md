# GET /accounts/{account_id}/members/{member_id}

**Resource:** [Account Members](../resources/Account-Members.md)
**Member Details**
**Operation ID:** `account-members-member-details`

Get information about a specific member of an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `member_id` | path | iam_membership_components-schemas-identifier | Yes |  |
| `account_id` | path | iam_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Member Details response |
| 4XX | Member Details response failure |

**Success Response Schema:**

[iam_single_member_response_with_policies](../schemas/iam/iam-single-member-response-with-policies.md)

## Security

- **api_email**
- **api_key**
