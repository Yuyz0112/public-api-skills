# GET /auth.test

**Resource:** [auth](../resources/auth.md)
**Operation ID:** `auth_test`

Checks authentication & identity.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `none` |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Standard success response when used with a user token |
| default | Standard failure response when used with an invalid token |

## Security

- **slackAuth**: none
