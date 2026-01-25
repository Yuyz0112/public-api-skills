# magic_health_check_base

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No | Determines whether to run healthchecks for a tunnel. |
| `rate` | enum: low, mid, high | No | How frequent the health check is run. The default value is `mid`. |
| `target` | any | No | The destination address in a request type health check. After the healthcheck is decapsulated at the customer end of the tunnel, the ICMP echo will be forwarded to this address. This field defaults to `customer_gre_endpoint address`. This field is ignored for bidirectional healthchecks as the interface_address (not assigned to the Cloudflare side of the tunnel) is used as the target. Must be in object form if the x-magic-new-hc-target header is set to true and string form if x-magic-new-hc-target is absent or set to false. |
| `type` | enum: reply, request | No | The type of healthcheck to run, reply or request. The default value is `reply`. |

