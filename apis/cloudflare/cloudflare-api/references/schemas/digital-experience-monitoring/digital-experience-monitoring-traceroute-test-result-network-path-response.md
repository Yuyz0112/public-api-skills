# digital-experience-monitoring_traceroute_test_result_network_path_response

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `deviceName` | string | No | name of the device associated with this network path response |
| `hops` | object[] | Yes | an array of the hops taken by the device to reach the end destination |
| `resultId` | [digital-experience-monitoring_uuid](digital-experience-monitoring-uuid.md) | Yes |  |
| `testId` | [digital-experience-monitoring_uuid](digital-experience-monitoring-uuid.md) | No |  |
| `testName` | string | No | name of the tracroute test |

## Nested Fields

### `hops`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `asn` | integer | No |  |
| `aso` | string | No |  |
| `ipAddress` | string | No |  |
| `location` | object | No |  |
| `mile` | enum: client-to-app, client-to-cf-egress, client-to-cf-ingress... | No |  |
| `name` | string | No |  |
| `packetLossPct` | number (float) | No |  |
| `rttMs` | integer | No |  |
| `ttl` | integer | Yes |  |

#### `hops.location`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `city` | string | No |  |
| `state` | string | No |  |
| `zip` | string | No |  |

