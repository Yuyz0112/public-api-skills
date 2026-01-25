# digital-experience-monitoring_http_details_response

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `host` | string | No | The url of the HTTP synthetic application test |
| `httpStats` | object | No |  |
| `httpStatsByColo` | object[] | No |  |
| `interval` | string | No | The interval at which the HTTP synthetic application test is set to run. |
| `kind` | enum: http | No |  |
| `method` | string | No | The HTTP method to use when running the test |
| `name` | string | No | The name of the HTTP synthetic application test |
| `target_policies` | object[] | No |  |
| `targeted` | boolean | No |  |

## Nested Fields

### `httpStats`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `availabilityPct` | [digital-experience-monitoring_test_stat_pct_over_time](digital-experience-monitoring-test-stat-pct-over-time.md) | Yes |  |
| `dnsResponseTimeMs` | [digital-experience-monitoring_test_stat_over_time](digital-experience-monitoring-test-stat-over-time.md) | Yes |  |
| `httpStatusCode` | object[] | Yes |  |
| `resourceFetchTimeMs` | [digital-experience-monitoring_test_stat_over_time](digital-experience-monitoring-test-stat-over-time.md) | Yes |  |
| `serverResponseTimeMs` | [digital-experience-monitoring_test_stat_over_time](digital-experience-monitoring-test-stat-over-time.md) | Yes |  |
| `uniqueDevicesTotal` | integer | Yes | Count of unique devices that have run this test in the given time period |

#### `httpStats.httpStatusCode`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `status200` | integer | Yes |  |
| `status300` | integer | Yes |  |
| `status400` | integer | Yes |  |
| `status500` | integer | Yes |  |
| `timestamp` | string | Yes |  |

### `httpStatsByColo`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `availabilityPct` | [digital-experience-monitoring_test_stat_pct_over_time](digital-experience-monitoring-test-stat-pct-over-time.md) | Yes |  |
| `colo` | string | Yes |  |
| `dnsResponseTimeMs` | [digital-experience-monitoring_test_stat_over_time](digital-experience-monitoring-test-stat-over-time.md) | Yes |  |
| `httpStatusCode` | object[] | Yes |  |
| `resourceFetchTimeMs` | [digital-experience-monitoring_test_stat_over_time](digital-experience-monitoring-test-stat-over-time.md) | Yes |  |
| `serverResponseTimeMs` | [digital-experience-monitoring_test_stat_over_time](digital-experience-monitoring-test-stat-over-time.md) | Yes |  |
| `uniqueDevicesTotal` | integer | Yes | Count of unique devices that have run this test in the given time period |

#### `httpStatsByColo.httpStatusCode`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `status200` | integer | Yes |  |
| `status300` | integer | Yes |  |
| `status400` | integer | Yes |  |
| `status500` | integer | Yes |  |
| `timestamp` | string | Yes |  |

### `target_policies`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `default` | boolean | Yes | Whether the policy is the default for the account |
| `id` | string | Yes |  |
| `name` | string | Yes |  |

