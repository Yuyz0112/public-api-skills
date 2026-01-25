# repository-rule-ruleset-info

User-defined metadata to store domain-specific information limited to 8 keys with scalar values.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ruleset_source_type` | enum: Repository, Organization | No | The type of source for the ruleset that includes this rule. |
| `ruleset_source` | string | No | The name of the source of the ruleset that includes this rule. |
| `ruleset_id` | integer | No | The ID of the ruleset that includes this rule. |

