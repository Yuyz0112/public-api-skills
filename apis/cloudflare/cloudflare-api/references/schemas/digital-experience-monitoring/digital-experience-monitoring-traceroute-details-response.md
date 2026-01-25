# digital-experience-monitoring_traceroute_details_response

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `host` | string | Yes | The host of the Traceroute synthetic application test |
| `interval` | string | Yes | The interval at which the Traceroute synthetic application test is set to run. |
| `kind` | enum: traceroute | Yes |  |
| `name` | string | Yes | The name of the Traceroute synthetic application test |
| `target_policies` | object[] | No |  |
| `targeted` | boolean | No |  |
| `tracerouteStats` | object | No |  |
| `tracerouteStatsByColo` | object[] | No |  |

## Nested Fields

### `target_policies`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `default` | boolean | Yes | Whether the policy is the default for the account |
| `id` | string | Yes |  |
| `name` | string | Yes |  |

### `tracerouteStats`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `availabilityPct` | [digital-experience-monitoring_test_stat_pct_over_time](digital-experience-monitoring-test-stat-pct-over-time.md) | Yes |  |
| `hopsCount` | [digital-experience-monitoring_test_stat_over_time](digital-experience-monitoring-test-stat-over-time.md) | Yes |  |
| `packetLossPct` | [digital-experience-monitoring_test_stat_pct_over_time](digital-experience-monitoring-test-stat-pct-over-time.md) | Yes |  |
| `roundTripTimeMs` | [digital-experience-monitoring_test_stat_over_time](digital-experience-monitoring-test-stat-over-time.md) | Yes |  |
| `uniqueDevicesTotal` | integer | Yes | Count of unique devices that have run this test in the given time period |

### `tracerouteStatsByColo`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `availabilityPct` | [digital-experience-monitoring_test_stat_pct_over_time](digital-experience-monitoring-test-stat-pct-over-time.md) | Yes |  |
| `colo` | string | Yes |  |
| `hopsCount` | [digital-experience-monitoring_test_stat_over_time](digital-experience-monitoring-test-stat-over-time.md) | Yes |  |
| `packetLossPct` | [digital-experience-monitoring_test_stat_pct_over_time](digital-experience-monitoring-test-stat-pct-over-time.md) | Yes |  |
| `roundTripTimeMs` | [digital-experience-monitoring_test_stat_over_time](digital-experience-monitoring-test-stat-over-time.md) | Yes |  |
| `uniqueDevicesTotal` | integer | Yes | Count of unique devices that have run this test in the given time period |

