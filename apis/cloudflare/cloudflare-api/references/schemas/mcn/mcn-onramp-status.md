# mcn_onramp_status

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `apply_progress` | [mcn_apply_progress](mcn-apply-progress.md) | Yes |  |
| `lifecycle_errors` | object | No |  |
| `lifecycle_state` | [mcn_onramp_lifecycle_state](mcn-onramp-lifecycle-state.md) | Yes |  |
| `plan_progress` | [mcn_plan_progress](mcn-plan-progress.md) | Yes |  |
| `routes` | mcn_conduit_route_id[] | Yes |  |
| `tunnels` | mcn_conduit_tunnel_id[] | Yes |  |

