# Get2UsersIdTweetsResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | Tweet[] | No |  |
| `errors` | Problem[] | No |  |
| `includes` | [Expansions](Expansions.md) | No |  |
| `meta` | object | No |  |

## Nested Fields

### `meta`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `newest_id` | [NewestId](NewestId.md) | No |  |
| `next_token` | [NextToken](NextToken.md) | No |  |
| `oldest_id` | [OldestId](OldestId.md) | No |  |
| `previous_token` | [PreviousToken](PreviousToken.md) | No |  |
| `result_count` | [ResultCount](ResultCount.md) | No |  |

