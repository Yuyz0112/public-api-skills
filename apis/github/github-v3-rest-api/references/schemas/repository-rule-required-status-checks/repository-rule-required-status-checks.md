# repository-rule-required-status-checks

Choose which status checks must pass before the ref is updated. When enabled, commits must first be pushed to another ref where the checks pass.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: required_status_checks | Yes |  |
| `parameters` | object | No |  |

## Nested Fields

### `parameters`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `do_not_enforce_on_create` | boolean | No | Allow repositories and branches to be created if a check would otherwise prohibit it. |
| `required_status_checks` | repository-rule-params-status-check-configuration[] | Yes | Status checks that are required. |
| `strict_required_status_checks_policy` | boolean | Yes | Whether pull requests targeting a matching branch must be tested with the latest code. This setting will not take effect unless at least one status check is enabled. |

