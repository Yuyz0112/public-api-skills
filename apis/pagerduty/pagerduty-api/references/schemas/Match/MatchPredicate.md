# MatchPredicate

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: all, any, not... | Yes |  |
| `matcher` | string | No | Required if the type is `contains`, `exactly` or `regex`. |
| `part` | enum: body, subject, from_addresses | Yes | The email field that will attempt to use the matcher expression. Required if the type is `contains`, `exactly` or `regex`. |
| `children` | MatchPredicate[] | Yes | Additional matchers to be run. Must be not empty if the type is `all`, `any`, or `not`. |

