# access_identity-provider

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `config` | object | Yes | The configuration parameters for the identity provider. To view the required parameters for a specific provider, refer to our [developer documentation](https://developers.cloudflare.com/cloudflare-one/identity/idp-integration/). |
| `id` | [access_uuid](access-uuid.md) | No |  |
| `name` | [access_components-schemas-name](access-components-schemas-name.md) | Yes |  |
| `scim_config` | object | No | The configuration settings for enabling a System for Cross-Domain Identity Management (SCIM) with the identity provider. |
| `type` | enum: onetimepin, azureAD, saml... | Yes | The type of identity provider. To determine the value for a specific provider, refer to our [developer documentation](https://developers.cloudflare.com/cloudflare-one/identity/idp-integration/). |

## Nested Fields

### `scim_config`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No | A flag to enable or disable SCIM for the identity provider. |
| `identity_update_behavior` | enum: automatic, reauth, no_action | No | Indicates how a SCIM event updates a user identity used for policy evaluation. Use "automatic" to automatically update a user's identity and augment it with fields from the SCIM user resource. Use "reauth" to force re-authentication on group membership updates, user identity update will only occur after successful re-authentication. With "reauth" identities will not contain fields from the SCIM user resource. With "no_action" identities will not be changed by SCIM updates in any way and users will not be prompted to reauthenticate. |
| `scim_base_url` | string | No | The base URL of Cloudflare's SCIM V2.0 API endpoint. |
| `seat_deprovision` | boolean | No | A flag to remove a user's seat in Zero Trust when they have been deprovisioned in the Identity Provider.  This cannot be enabled unless user_deprovision is also enabled. |
| `secret` | string | No | A read-only token generated when the SCIM integration is enabled for the first time.  It is redacted on subsequent requests.  If you lose this you will need to refresh it at /access/identity_providers/:idpID/refresh_scim_secret. |
| `user_deprovision` | boolean | No | A flag to enable revoking a user's session in Access and Gateway when they have been deprovisioned in the Identity Provider. |

