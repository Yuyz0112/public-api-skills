# workflow-run-usage

Workflow Run Usage

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `billable` | object | Yes |  |
| `run_duration_ms` | integer | No |  |

## Nested Fields

### `billable`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `UBUNTU` | object | No |  |
| `MACOS` | object | No |  |
| `WINDOWS` | object | No |  |

#### `billable.UBUNTU`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `total_ms` | integer | Yes |  |
| `jobs` | integer | Yes |  |
| `job_runs` | object[] | No |  |

#### `billable.MACOS`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `total_ms` | integer | Yes |  |
| `jobs` | integer | Yes |  |
| `job_runs` | object[] | No |  |

#### `billable.WINDOWS`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `total_ms` | integer | Yes |  |
| `jobs` | integer | Yes |  |
| `job_runs` | object[] | No |  |

