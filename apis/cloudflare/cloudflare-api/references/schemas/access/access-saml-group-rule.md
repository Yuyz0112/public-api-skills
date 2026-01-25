# access_saml_group_rule

Matches a SAML group.
Requires a SAML identity provider.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `saml` | object | Yes |  |

## Nested Fields

### `saml`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `attribute_name` | string | Yes | The name of the SAML attribute. |
| `attribute_value` | string | Yes | The SAML attribute value to look for. |
| `identity_provider_id` | string | Yes | The ID of your SAML identity provider. |

