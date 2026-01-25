# GET /oauth.token

**Resource:** [oauth](../resources/oauth.md)
**Operation ID:** `oauth_token`

Exchanges a temporary OAuth verifier code for a workspace token.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `client_id` | query | string | No | Issued when you created your application. |
| `client_secret` | query | string | No | Issued when you created your application. |
| `code` | query | string | No | The `code` param returned via the OAuth callback. |
| `redirect_uri` | query | string | No | This must match the originally submitted URI (if one was sent). |
| `single_channel` | query | boolean | No | Request the user to add your app only to a single channel. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Success example using a workspace app produces a very different kind of response |
| default | Typical error response |

## Security

- **slackAuth**: none
