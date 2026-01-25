# FilteredStreamingTweetResponse

A Tweet or error that can be returned by the streaming Tweet API. The values returned with a successful streamed Tweet includes the user provided rules that the Tweet matched.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | [Tweet](Tweet.md) | No |  |
| `errors` | Problem[] | No |  |
| `includes` | [Expansions](Expansions.md) | No |  |
| `matching_rules` | object[] | No | The list of rules which matched the Tweet |

## Nested Fields

### `matching_rules`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [RuleId](RuleId.md) | Yes |  |
| `tag` | [RuleTag](RuleTag.md) | No |  |

