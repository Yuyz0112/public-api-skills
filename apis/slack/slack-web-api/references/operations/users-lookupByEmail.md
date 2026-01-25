# GET /users.lookupByEmail

**Resource:** [users](../resources/users.md)
**Operation ID:** `users_lookupByEmail`

Find a user with an email address.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `users:read.email` |
| `email` | query | string | Yes | An email address belonging to a user in the workspace |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: users:read.email
