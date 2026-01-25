# addressing_provisioning

Status of a Service Binding's deployment to the Cloudflare network

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `state` | enum: provisioning, active | No | When a binding has been deployed to a majority of Cloudflare datacenters, the binding will become active and can be used with its associated service.
 |

