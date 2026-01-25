# mcn_onramp

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `attached_hubs` | mcn_resource_id[] | No |  |
| `attached_vpcs` | mcn_resource_id[] | No |  |
| `cloud_asn` | integer (uint32) | No |  |
| `cloud_type` | [mcn_onramp_cloud_type](mcn-onramp-cloud-type.md) | Yes |  |
| `description` | string | No |  |
| `dynamic_routing` | boolean | Yes |  |
| `hub` | [mcn_resource_id](mcn-resource-id.md) | No |  |
| `id` | [mcn_onramp_id](mcn-onramp-id.md) | Yes |  |
| `install_routes_in_cloud` | boolean | Yes |  |
| `install_routes_in_magic_wan` | boolean | Yes |  |
| `last_applied_at` | string | No |  |
| `last_exported_at` | string | No |  |
| `last_planned_at` | string | No |  |
| `manage_hub_to_hub_attachments` | boolean | No |  |
| `manage_vpc_to_hub_attachments` | boolean | No |  |
| `name` | string | Yes |  |
| `planned_monthly_cost_estimate` | [mcn_cost_diff](mcn-cost-diff.md) | No |  |
| `planned_resources` | mcn_resource_diff[] | No |  |
| `planned_resources_unavailable` | boolean | No |  |
| `post_apply_monthly_cost_estimate` | [mcn_cost](mcn-cost.md) | No |  |
| `post_apply_resources` | object | No |  |
| `post_apply_resources_unavailable` | boolean | No |  |
| `region` | string | No |  |
| `status` | [mcn_onramp_status](mcn-onramp-status.md) | No |  |
| `type` | [mcn_onramp_type](mcn-onramp-type.md) | Yes |  |
| `updated_at` | string | Yes |  |
| `vpc` | [mcn_resource_id](mcn-resource-id.md) | No |  |
| `vpcs_by_id` | object | No |  |
| `vpcs_by_id_unavailable` | mcn_resource_id[] | No | The list of vpc IDs for which resource details failed to generate. |

