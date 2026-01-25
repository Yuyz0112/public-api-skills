# access_scim_config_authentication_http_basic

Attributes for configuring HTTP Basic authentication scheme for SCIM provisioning to an application.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `password` | string | Yes | Password used to authenticate with the remote SCIM service. |
| `scheme` | enum: httpbasic | Yes | The authentication scheme to use when making SCIM requests to this application. |
| `user` | string | Yes | User name used to authenticate with the remote SCIM service. |

