# GET /memberships

**Resource:** [User's Account Memberships](../resources/User-s-Account-Memberships.md)
**List Memberships**
**Operation ID:** `user'-s-account-memberships-list-memberships`

List memberships of accounts the user can access.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account.name` | query | iam_properties-name | No |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |
| `order` | query | enum: id, account.name, status | No |  |
| `direction` | query | enum: asc, desc | No |  |
| `name` | query | iam_properties-name | No |  |
| `status` | query | enum: accepted, pending, rejected | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Memberships response |
| 4XX | List Memberships response failure |

## Security

- **api_email**
- **api_key**
