# access_users

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `active` | boolean | No | Determines the status of the SCIM User resource. |
| `displayName` | string | No | The name of the SCIM User resource. |
| `emails` | object[] | No |  |
| `externalId` | string | No | The IdP-generated Id of the SCIM resource. |
| `id` | [access_id](access-id.md) | No |  |
| `meta` | [access_meta](access-meta.md) | No |  |
| `schemas` | string[] | No | The list of URIs which indicate the attributes contained within a SCIM resource. |

## Nested Fields

### `emails`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `primary` | boolean | No | Indicates if the email address is the primary email belonging to the SCIM User resource. |
| `type` | string | No | Indicates the type of the email address. |
| `value` | string (email) | No | The email address of the SCIM User resource. |

