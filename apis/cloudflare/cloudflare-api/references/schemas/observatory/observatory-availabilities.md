# observatory_availabilities

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `quota` | object | No |  |
| `regions` | observatory_labeled_region[] | No |  |
| `regionsPerPlan` | object | No | Available regions. |

## Nested Fields

### `quota`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `plan` | string | No | Cloudflare plan. |
| `quotasPerPlan` | object | No | The number of tests available per plan. |
| `remainingSchedules` | number | No | The number of remaining schedules available. |
| `remainingTests` | number | No | The number of remaining tests available. |
| `scheduleQuotasPerPlan` | object | No | The number of schedules available per plan. |

#### `quota.quotasPerPlan`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `value` | [observatory_plan-properties-info](observatory-plan-properties-info.md) | No |  |

#### `quota.scheduleQuotasPerPlan`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `value` | [observatory_plan-properties-info](observatory-plan-properties-info.md) | No |  |

### `regionsPerPlan`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `business` | observatory_labeled_region[] | No |  |
| `enterprise` | observatory_labeled_region[] | No |  |
| `free` | observatory_labeled_region[] | No |  |
| `pro` | observatory_labeled_region[] | No |  |

