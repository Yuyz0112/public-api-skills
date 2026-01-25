# access_scim_config_authentication_oauth2

Attributes for configuring OAuth 2 authentication scheme for SCIM provisioning to an application.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `authorization_url` | string | Yes | URL used to generate the auth code used during token generation. |
| `client_id` | string | Yes | Client ID used to authenticate when generating a token for authenticating with the remote SCIM service. |
| `client_secret` | string | Yes | Secret used to authenticate when generating a token for authenticating with the remove SCIM service. |
| `scheme` | enum: oauth2 | Yes | The authentication scheme to use when making SCIM requests to this application. |
| `scopes` | string[] | No | The authorization scopes to request when generating the token used to authenticate with the remove SCIM service. |
| `token_url` | string | Yes | URL used to generate the token used to authenticate with the remote SCIM service. |

