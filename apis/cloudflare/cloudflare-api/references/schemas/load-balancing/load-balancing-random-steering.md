# load-balancing_random_steering

Configures pool weights.
- `steering_policy="random"`: A random pool is selected with probability proportional to pool weights.
- `steering_policy="least_outstanding_requests"`: Use pool weights to scale each pool's outstanding requests.
- `steering_policy="least_connections"`: Use pool weights to scale each pool's open connections.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `default_weight` | number | No | The default weight for pools in the load balancer that are not specified in the pool_weights map. |
| `pool_weights` | object | No | A mapping of pool IDs to custom weights. The weight is relative to other pools in the load balancer. |

