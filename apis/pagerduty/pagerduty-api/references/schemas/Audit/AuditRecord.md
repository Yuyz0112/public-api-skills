# AuditRecord

An Audit Trail record

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes |  |
| `self` | string | No | Record URL. |
| `execution_time` | string (date-time) | Yes | The date/time the action executed, in ISO8601 format and millisecond precision. |
| `execution_context` | object | No | Action execution context |
| `actors` | Reference[] | No |  |
| `method` | object | Yes | The method information |
| `root_resource` | [Reference](Reference.md) | Yes |  |
| `action` | string | Yes |  |
| `details` | object | No | Additional details to provide further information about the action or
the resource that has been audited.
 |

## Nested Fields

### `execution_context`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `request_id` | string | No | Request Id |
| `remote_address` | string | No | remote address |

### `method`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No |  |
| `truncated_token` | string | No | Truncated token containing the last 4 chars of the token's actual value. |
| `type` | [schema](schema.md) | Yes |  |

### `details`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `resource` | [Reference](Reference.md) | Yes |  |
| `fields` | object[] | No | A set of fields that have been affected.
The fields that have not been affected MAY be returned.
 |
| `references` | object[] | No | A set of references that have been affected. |

#### `details.fields`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | Name of the resource field |
| `description` | string | No | Human readable description of the resource field |
| `value` | string | No | new or updated value of the field |
| `before_value` | string | No | previous or deleted value of the field |

#### `details.references`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | Name of the reference field |
| `description` | string | No | Human readable description of the references field |
| `added` | Reference[] | No |  |
| `removed` | Reference[] | No |  |

