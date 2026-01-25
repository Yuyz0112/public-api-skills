# KeywordUpsertRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes |  |
| `event_type` | [AutomodEventType](AutomodEventType.md) | Yes |  |
| `actions` | array,null | No |  |
| `enabled` | boolean,null | No |  |
| `exempt_roles` | array,null | No |  |
| `exempt_channels` | array,null | No |  |
| `trigger_type` | enum: 1 | Yes |  |
| `trigger_metadata` | any | No |  |

