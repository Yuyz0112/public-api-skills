# digital-experience-monitoring_tests_response

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `overviewMetrics` | object | Yes |  |
| `tests` | object[] | Yes | array of test results objects. |

## Nested Fields

### `overviewMetrics`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avgHttpAvailabilityPct` | number (float) | No | percentage availability for all HTTP test results in response |
| `avgTracerouteAvailabilityPct` | number (float) | No | percentage availability for all traceroutes results in response |
| `testsTotal` | integer | Yes | number of  tests. |

### `tests`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | string | Yes | date the test was created. |
| `description` | string | Yes | the test description defined during configuration |
| `enabled` | boolean | Yes | if true, then the test will run on targeted devices. Else, the test will not run. |
| `host` | string | Yes |  |
| `httpResults` | object | No |  |
| `httpResultsByColo` | object[] | No |  |
| `id` | [digital-experience-monitoring_uuid](digital-experience-monitoring-uuid.md) | Yes |  |
| `interval` | string | Yes | The interval at which the synthetic application test is set to run. |
| `kind` | enum: http, traceroute | Yes | test type, http or traceroute |
| `method` | string | No | for HTTP, the method to use when running the test |
| `name` | string | Yes | name given to this test |
| `target_policies` | object[] | No |  |
| `targeted` | boolean | No |  |
| `tracerouteResults` | object | No |  |
| `tracerouteResultsByColo` | object[] | No |  |
| `updated` | string | Yes |  |

#### `tests.httpResults`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `resourceFetchTime` | [digital-experience-monitoring_timing_aggregates](digital-experience-monitoring-timing-aggregates.md) | Yes |  |

#### `tests.httpResultsByColo`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `colo` | string | Yes | Cloudflare colo |
| `resourceFetchTime` | [digital-experience-monitoring_timing_aggregates](digital-experience-monitoring-timing-aggregates.md) | Yes |  |

#### `tests.target_policies`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `default` | boolean | Yes | Whether the policy is the default for the account |
| `id` | string | Yes |  |
| `name` | string | Yes |  |

#### `tests.tracerouteResults`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `roundTripTime` | [digital-experience-monitoring_timing_aggregates](digital-experience-monitoring-timing-aggregates.md) | Yes |  |

#### `tests.tracerouteResultsByColo`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `colo` | string | Yes | Cloudflare colo |
| `roundTripTime` | [digital-experience-monitoring_timing_aggregates](digital-experience-monitoring-timing-aggregates.md) | Yes |  |

