# code-security-configuration

A code security configuration

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No | The ID of the code security configuration |
| `name` | string | No | The name of the code security configuration. Must be unique within the organization. |
| `target_type` | enum: global, organization, enterprise | No | The type of the code security configuration. |
| `description` | string | No | A description of the code security configuration |
| `advanced_security` | enum: enabled, disabled, code_security... | No | The enablement status of GitHub Advanced Security |
| `dependency_graph` | enum: enabled, disabled, not_set | No | The enablement status of Dependency Graph |
| `dependency_graph_autosubmit_action` | enum: enabled, disabled, not_set | No | The enablement status of Automatic dependency submission |
| `dependency_graph_autosubmit_action_options` | object | No | Feature options for Automatic dependency submission |
| `dependabot_alerts` | enum: enabled, disabled, not_set | No | The enablement status of Dependabot alerts |
| `dependabot_security_updates` | enum: enabled, disabled, not_set | No | The enablement status of Dependabot security updates |
| `dependabot_delegated_alert_dismissal` | enum: enabled, disabled, not_set | No | The enablement status of Dependabot delegated alert dismissal |
| `code_scanning_options` | object | No | Feature options for code scanning |
| `code_scanning_default_setup` | enum: enabled, disabled, not_set | No | The enablement status of code scanning default setup |
| `code_scanning_default_setup_options` | object | No | Feature options for code scanning default setup |
| `code_scanning_delegated_alert_dismissal` | enum: enabled, disabled, not_set | No | The enablement status of code scanning delegated alert dismissal |
| `secret_scanning` | enum: enabled, disabled, not_set | No | The enablement status of secret scanning |
| `secret_scanning_push_protection` | enum: enabled, disabled, not_set | No | The enablement status of secret scanning push protection |
| `secret_scanning_delegated_bypass` | enum: enabled, disabled, not_set | No | The enablement status of secret scanning delegated bypass |
| `secret_scanning_delegated_bypass_options` | object | No | Feature options for secret scanning delegated bypass |
| `secret_scanning_validity_checks` | enum: enabled, disabled, not_set | No | The enablement status of secret scanning validity checks |
| `secret_scanning_non_provider_patterns` | enum: enabled, disabled, not_set | No | The enablement status of secret scanning non-provider patterns |
| `secret_scanning_generic_secrets` | enum: enabled, disabled, not_set | No | The enablement status of Copilot secret scanning |
| `secret_scanning_delegated_alert_dismissal` | enum: enabled, disabled, not_set | No | The enablement status of secret scanning delegated alert dismissal |
| `private_vulnerability_reporting` | enum: enabled, disabled, not_set | No | The enablement status of private vulnerability reporting |
| `enforcement` | enum: enforced, unenforced | No | The enforcement status for a security configuration |
| `url` | string (uri) | No | The URL of the configuration |
| `html_url` | string (uri) | No | The URL of the configuration |
| `created_at` | string (date-time) | No |  |
| `updated_at` | string (date-time) | No |  |

## Nested Fields

### `dependency_graph_autosubmit_action_options`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `labeled_runners` | boolean | No | Whether to use runners labeled with 'dependency-submission' or standard GitHub runners. |

### `code_scanning_options`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `allow_advanced` | boolean | No | Whether to allow repos which use advanced setup |

### `code_scanning_default_setup_options`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `runner_type` | enum: standard, labeled, not_set | No | Whether to use labeled runners or standard GitHub runners. |
| `runner_label` | string | No | The label of the runner to use for code scanning when runner_type is 'labeled'. |

### `secret_scanning_delegated_bypass_options`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `reviewers` | object[] | No | The bypass reviewers for secret scanning delegated bypass |

#### `secret_scanning_delegated_bypass_options.reviewers`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `reviewer_id` | integer | Yes | The ID of the team or role selected as a bypass reviewer |
| `reviewer_type` | enum: TEAM, ROLE | Yes | The type of the bypass reviewer |

