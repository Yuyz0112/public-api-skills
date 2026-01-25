# digital-experience-monitoring_traceroute_test_network_path_response

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `deviceName` | string | No |  |
| `id` | [digital-experience-monitoring_uuid](digital-experience-monitoring-uuid.md) | Yes |  |
| `interval` | string | No | The interval at which the Traceroute synthetic application test is set to run. |
| `kind` | enum: traceroute | No |  |
| `name` | string | No |  |
| `networkPath` | object | No |  |
| `url` | string | No | The host of the Traceroute synthetic application test |

## Nested Fields

### `networkPath`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sampling` | object | No | Specifies the sampling applied, if any, to the slots response. When sampled, results shown represent the first test run to the start of each sampling interval. |
| `slots` | object[] | Yes |  |

#### `networkPath.sampling`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `unit` | enum: hours | Yes |  |
| `value` | integer | Yes |  |

#### `networkPath.slots`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `clientToAppRttMs` | integer | Yes | Round trip time in ms of the client to app mile |
| `clientToCfEgressRttMs` | integer | Yes | Round trip time in ms of the client to Cloudflare egress mile |
| `clientToCfIngressRttMs` | integer | Yes | Round trip time in ms of the client to Cloudflare ingress mile |
| `clientToIspRttMs` | integer | No | Round trip time in ms of the client to ISP mile |
| `id` | [digital-experience-monitoring_uuid](digital-experience-monitoring-uuid.md) | Yes |  |
| `timestamp` | string | Yes |  |

