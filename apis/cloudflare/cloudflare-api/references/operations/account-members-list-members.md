# GET /accounts/{account_id}/members

**Resource:** [Account Members](../resources/Account-Members.md)
**List Members**
**Operation ID:** `account-members-list-members`

List all members of an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |
| `order` | query | enum: user.first_name, user.last_name, user.email... | No |  |
| `status` | query | enum: accepted, pending, rejected | No |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |
| `direction` | query | enum: asc, desc | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Members response |
| 4XX | List Members response failure |

**Success Response Schema:**

[iam_collection_member_response_with_policies](../schemas/iam/iam-collection-member-response-with-policies.md)

## Security

- **api_email**
- **api_key**
