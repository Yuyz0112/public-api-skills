# access_scim_config_authentication_access_service_token

Attributes for configuring Access Service Token authentication scheme for SCIM provisioning to an application.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `client_id` | string | Yes | Client ID of the Access service token used to authenticate with the remote service. |
| `client_secret` | string | Yes | Client secret of the Access service token used to authenticate with the remote service. |
| `scheme` | enum: access_service_token | Yes | The authentication scheme to use when making SCIM requests to this application. |

