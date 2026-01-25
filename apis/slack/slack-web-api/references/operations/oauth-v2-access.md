# GET /oauth.v2.access

**Resource:** [oauth.v2](../resources/oauth-v2.md)
**Operation ID:** `oauth_v2_access`

Exchanges a temporary OAuth verifier code for an access token.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `client_id` | query | string | No | Issued when you created your application. |
| `client_secret` | query | string | No | Issued when you created your application. |
| `code` | query | string | Yes | The `code` param returned via the OAuth callback. |
| `redirect_uri` | query | string | No | This must match the originally submitted URI (if one was sent). |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful token request with scopes for both a bot user and a user token |
| default | Typical error response |

## Security

- **slackAuth**: none
