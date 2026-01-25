# load-balancing_load_shedding

Configures load shedding policies and percentages for the pool.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `default_percent` | number | No | The percent of traffic to shed from the pool, according to the default policy. Applies to new sessions and traffic without session affinity. |
| `default_policy` | enum: random, hash | No | The default policy to use when load shedding. A random policy randomly sheds a given percent of requests. A hash policy computes a hash over the CF-Connecting-IP address and sheds all requests originating from a percent of IPs. |
| `session_percent` | number | No | The percent of existing sessions to shed from the pool, according to the session policy. |
| `session_policy` | enum: hash | No | Only the hash policy is supported for existing sessions (to avoid exponential decay). |

