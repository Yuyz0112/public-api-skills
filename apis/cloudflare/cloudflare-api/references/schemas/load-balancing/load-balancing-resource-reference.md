# load-balancing_resource_reference

A reference to a load balancer resource.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `reference_type` | enum: referral, referrer | No | When listed as a reference, the type (direction) of the reference. |
| `references` | object[] | No | A list of references to (referrer) or from (referral) this resource. |
| `resource_id` | string | No |  |
| `resource_name` | string | No | The human-identifiable name of the resource. |
| `resource_type` | enum: load_balancer, monitor, pool | No | The type of the resource. |

