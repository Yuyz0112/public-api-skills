# UserTakedownComplianceSchema

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `event_at` | string (date-time) | Yes | Event time. |
| `user` | object | Yes |  |
| `withheld_in_countries` | CountryCode[] | Yes |  |

## Nested Fields

### `user`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [UserId](UserId.md) | Yes |  |

