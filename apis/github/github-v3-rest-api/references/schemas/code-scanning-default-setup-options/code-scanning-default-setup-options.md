# code-scanning-default-setup-options

Feature options for code scanning default setup

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `runner_type` | enum: standard, labeled, not_set | No | Whether to use labeled runners or standard GitHub runners. |
| `runner_label` | string | No | The label of the runner to use for code scanning default setup when runner_type is 'labeled'. |

