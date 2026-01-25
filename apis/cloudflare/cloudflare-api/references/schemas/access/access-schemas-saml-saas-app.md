# access_schemas-saml_saas_app

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `auth_type` | enum: saml, oidc | No | Optional identifier indicating the authentication protocol used for the saas app. Required for OIDC. Default if unset is "saml" |
| `consumer_service_url` | string | No | The service provider's endpoint that is responsible for receiving and parsing a SAML assertion. |
| `created_at` | [access_timestamp](access-timestamp.md) | No |  |
| `custom_attributes` | object[] | No |  |
| `idp_entity_id` | string | No | The unique identifier for your SaaS application. |
| `name_id_format` | enum: id, email | No | The format of the name identifier sent to the SaaS application. |
| `name_id_transform_jsonata` | string | No | A [JSONata](https://jsonata.org/) expression that transforms an application's user identities into a NameID value for its SAML assertion. This expression should evaluate to a singular string. The output of this expression can override the `name_id_format` setting.
 |
| `public_key` | string | No | The Access public certificate that will be used to verify your identity. |
| `sp_entity_id` | string | No | A globally unique name for an identity or service provider. |
| `sso_endpoint` | string | No | The endpoint where your SaaS application will send login requests. |
| `updated_at` | [access_timestamp](access-timestamp.md) | No |  |

## Nested Fields

### `custom_attributes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `friendly_name` | string | No | The SAML FriendlyName of the attribute. |
| `name` | string | No | The name of the attribute. |
| `name_format` | enum: urn:oasis:names:tc:SAML:2.0:attrname-format:unspecified, urn:oasis:names:tc:SAML:2.0:attrname-format:basic, urn:oasis:names:tc:SAML:2.0:attrname-format:uri | No | A globally unique name for an identity or service provider. |
| `required` | boolean | No | If the attribute is required when building a SAML assertion. |
| `source` | object | No |  |

#### `custom_attributes.source`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | The name of the IdP attribute. |
| `name_by_idp` | object | No | A mapping from IdP ID to attribute name. |

