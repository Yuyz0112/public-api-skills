# aaa_mechanisms

List of IDs that will be used when dispatching a notification. IDs for email type will be the email address.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `email` | object[] | No |  |
| `pagerduty` | object[] | No |  |
| `webhooks` | object[] | No |  |

## Nested Fields

### `email`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | The email address |

### `pagerduty`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [aaa_uuid](aaa-uuid.md) | No |  |

### `webhooks`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [aaa_uuid](aaa-uuid.md) | No |  |

