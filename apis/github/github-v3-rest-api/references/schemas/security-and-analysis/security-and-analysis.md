# security-and-analysis

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `advanced_security` | object | No | Enable or disable GitHub Advanced Security for the repository.

For standalone Code Scanning or Secret Protection products, this parameter cannot be used.
 |
| `code_security` | object | No |  |
| `dependabot_security_updates` | object | No | Enable or disable Dependabot security updates for the repository. |
| `secret_scanning` | object | No |  |
| `secret_scanning_push_protection` | object | No |  |
| `secret_scanning_non_provider_patterns` | object | No |  |
| `secret_scanning_ai_detection` | object | No |  |

## Nested Fields

### `advanced_security`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `status` | enum: enabled, disabled | No |  |

### `code_security`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `status` | enum: enabled, disabled | No |  |

### `dependabot_security_updates`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `status` | enum: enabled, disabled | No | The enablement status of Dependabot security updates for the repository. |

### `secret_scanning`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `status` | enum: enabled, disabled | No |  |

### `secret_scanning_push_protection`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `status` | enum: enabled, disabled | No |  |

### `secret_scanning_non_provider_patterns`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `status` | enum: enabled, disabled | No |  |

### `secret_scanning_ai_detection`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `status` | enum: enabled, disabled | No |  |

