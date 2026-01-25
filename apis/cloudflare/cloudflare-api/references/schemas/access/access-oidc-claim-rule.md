# access_oidc_claim_rule

Matches an OIDC claim.
Requires an OIDC identity provider.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `oidc` | object | Yes |  |

## Nested Fields

### `oidc`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `claim_name` | string | Yes | The name of the OIDC claim. |
| `claim_value` | string | Yes | The OIDC claim value to look for. |
| `identity_provider_id` | string | Yes | The ID of your OIDC identity provider. |

