# access_oidc_saas_app

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `access_token_lifetime` | string | No | The lifetime of the OIDC Access Token after creation. Valid units are m,h. Must be greater than or equal to 1m and less than or equal to 24h. |
| `allow_pkce_without_client_secret` | boolean | No | If client secret should be required on the token endpoint when authorization_code_with_pkce grant is used. |
| `app_launcher_url` | string | No | The URL where this applications tile redirects users |
| `auth_type` | enum: saml, oidc | No | Identifier of the authentication protocol used for the saas app. Required for OIDC. |
| `client_id` | string | No | The application client id |
| `client_secret` | string | No | The application client secret, only returned on POST request. |
| `created_at` | [access_created_at](access-created-at.md) | No |  |
| `custom_claims` | object[] | No |  |
| `grant_types` | string[] | No | The OIDC flows supported by this application |
| `group_filter_regex` | string | No | A regex to filter Cloudflare groups returned in ID token and userinfo endpoint |
| `hybrid_and_implicit_options` | object | No |  |
| `public_key` | string | No | The Access public certificate that will be used to verify your identity. |
| `redirect_uris` | string[] | No | The permitted URL's for Cloudflare to return Authorization codes and Access/ID tokens |
| `refresh_token_options` | object | No |  |
| `scopes` | string[] | No | Define the user information shared with access, "offline_access" scope will be automatically enabled if refresh tokens are enabled |
| `updated_at` | [access_updated_at](access-updated-at.md) | No |  |

## Nested Fields

### `custom_claims`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | The name of the claim. |
| `required` | boolean | No | If the claim is required when building an OIDC token. |
| `scope` | enum: groups, profile, email... | No | The scope of the claim. |
| `source` | object | No |  |

#### `custom_claims.source`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | The name of the IdP claim. |
| `name_by_idp` | object | No | A mapping from IdP ID to claim name. |

### `hybrid_and_implicit_options`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `return_access_token_from_authorization_endpoint` | boolean | No | If an Access Token should be returned from the OIDC Authorization endpoint |
| `return_id_token_from_authorization_endpoint` | boolean | No | If an ID Token should be returned from the OIDC Authorization endpoint |

### `refresh_token_options`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `lifetime` | string | No | How long a refresh token will be valid for after creation. Valid units are m,h,d. Must be longer than 1m. |

