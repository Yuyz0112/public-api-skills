# Poll

Represent a Poll attached to a Tweet.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `duration_minutes` | integer (int32) | No |  |
| `end_datetime` | string (date-time) | No |  |
| `id` | [PollId](PollId.md) | Yes |  |
| `options` | PollOption[] | Yes |  |
| `voting_status` | enum: open, closed | No |  |

