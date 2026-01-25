# JqlQueryField

A field used in a JQL query. See [Advanced searching - fields reference](https://confluence.atlassian.com/x/dAiiLQ) for more information about fields in JQL queries.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `encodedName` | string | No | The encoded name of the field, which can be used directly in a JQL query. |
| `name` | string | Yes | The name of the field. |
| `property` | JqlQueryFieldEntityProperty[] | No | When the field refers to a value in an entity property, details of the entity property value. |

