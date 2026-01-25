# EmailParser

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: trigger, resolve | Yes |  |
| `match_predicate` | [MatchPredicate](MatchPredicate.md) | Yes |  |
| `value_extractors` | object[] | No | Additional values that will be pulled in to the Incident object. Exactly one value extractor must have a `value_name` of `incident_key`. |

## Nested Fields

### `value_extractors`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: entire, regex, between | Yes |  |
| `part` | enum: body, subject, from_addresses | Yes |  |
| `value_name` | string | Yes | The field name to set in the Incident object. Exactly one must use the `value_name` of `incident_key` |
| `regex` | string | No |  |
| `starts_after` | string | No |  |
| `ends_with` | string | No |  |

