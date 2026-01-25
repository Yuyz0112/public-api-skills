# GET /users.identity

**Resource:** [users](../resources/users.md)
**Operation ID:** `users_identity`

Get a user's identity.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | No | Authentication token. Requires scope: `identity.basic` |

## Responses

| Status | Description |
|--------|-------------|
| 200 | You will receive at a minimum the following information: |
| default | Typical error response |

## Security

- **slackAuth**: identity.basic
