# access_schemas-scim_config_authentication_oauth_bearer_token

Attributes for configuring OAuth Bearer Token authentication scheme for SCIM provisioning to an application.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `scheme` | enum: oauthbearertoken | Yes | The authentication scheme to use when making SCIM requests to this application. |
| `token` | string | Yes | Token used to authenticate with the remote SCIM service. |

