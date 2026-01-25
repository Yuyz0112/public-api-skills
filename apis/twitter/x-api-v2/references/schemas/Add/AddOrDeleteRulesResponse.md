# AddOrDeleteRulesResponse

A response from modifying user-specified stream filtering rules.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | Rule[] | No | All user-specified stream filtering rules that were created. |
| `errors` | Problem[] | No |  |
| `meta` | [RulesResponseMetadata](RulesResponseMetadata.md) | Yes |  |

