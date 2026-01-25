# GET /auth.revoke

**Resource:** [auth](../resources/auth.md)
**Operation ID:** `auth_revoke`

Revokes a token.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `none` |
| `test` | query | boolean | No | Setting this parameter to `1` triggers a _testing mode_ where the specified token will not actually be revoked. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: none
