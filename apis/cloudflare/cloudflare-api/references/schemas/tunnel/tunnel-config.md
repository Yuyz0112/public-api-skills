# tunnel_config

The tunnel configuration and ingress rules.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ingress` | tunnel_ingressRule[] | No | List of public hostname definitions. At least one ingress rule needs to be defined for the tunnel. |
| `originRequest` | [tunnel_originRequest](tunnel-originRequest.md) | No |  |
| `warp-routing` | object | No | Enable private network access from WARP users to private network routes. This is enabled if the tunnel has an assigned route. |

## Nested Fields

### `warp-routing`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No |  |

