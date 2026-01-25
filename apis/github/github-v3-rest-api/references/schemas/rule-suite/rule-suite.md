# rule-suite

Response

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No | The unique identifier of the rule insight. |
| `actor_id` | integer | No | The number that identifies the user. |
| `actor_name` | string | No | The handle for the GitHub user account. |
| `before_sha` | string | No | The previous commit SHA of the ref. |
| `after_sha` | string | No | The new commit SHA of the ref. |
| `ref` | string | No | The ref name that the evaluation ran on. |
| `repository_id` | integer | No | The ID of the repository associated with the rule evaluation. |
| `repository_name` | string | No | The name of the repository without the `.git` extension. |
| `pushed_at` | string (date-time) | No |  |
| `result` | enum: pass, fail, bypass | No | The result of the rule evaluations for rules with the `active` enforcement status. |
| `evaluation_result` | enum: pass, fail, bypass | No | The result of the rule evaluations for rules with the `active` and `evaluate` enforcement statuses, demonstrating whether rules would pass or fail if all rules in the rule suite were `active`. Null if no rules with `evaluate` enforcement status were run. |
| `rule_evaluations` | object[] | No | Details on the evaluated rules. |

## Nested Fields

### `rule_evaluations`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `rule_source` | object | No |  |
| `enforcement` | enum: active, evaluate, deleted ruleset | No | The enforcement level of this rule source. |
| `result` | enum: pass, fail | No | The result of the evaluation of the individual rule. |
| `rule_type` | string | No | The type of rule. |
| `details` | string | No | The detailed failure message for the rule. Null if the rule passed. |

#### `rule_evaluations.rule_source`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | string | No | The type of rule source. |
| `id` | integer | No | The ID of the rule source. |
| `name` | string | No | The name of the rule source. |

