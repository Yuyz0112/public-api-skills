# GET /accounts/{account_id}/access/users

**Resource:** [Zero Trust users](../resources/Zero-Trust-users.md)
**Get users**
**Operation ID:** `zero-trust-users-get-users`

Gets a list of users for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |
| `name` | query | string | No |  |
| `email` | query | string | No |  |
| `search` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get users response |
| 4XX | Get users response failure |

**Success Response Schema:**

[access_users_components-schemas-response_collection](../schemas/access/access-users-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
