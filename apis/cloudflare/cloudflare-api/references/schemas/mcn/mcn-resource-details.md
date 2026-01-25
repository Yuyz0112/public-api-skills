# mcn_resource_details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_id` | [mcn_account_id](mcn-account-id.md) | Yes |  |
| `cloud_type` | [mcn_cloud_type](mcn-cloud-type.md) | Yes |  |
| `config` | object | Yes |  |
| `deployment_provider` | [mcn_provider_id](mcn-provider-id.md) | Yes |  |
| `id` | [mcn_resource_id](mcn-resource-id.md) | Yes |  |
| `managed` | boolean | Yes |  |
| `managed_by` | mcn_cloud_platform_client[] | No |  |
| `monthly_cost_estimate` | [mcn_cost](mcn-cost.md) | Yes |  |
| `name` | string | Yes |  |
| `native_id` | string | Yes |  |
| `observations` | object | Yes |  |
| `provider_ids` | mcn_provider_id[] | Yes |  |
| `provider_names_by_id` | object | Yes |  |
| `region` | string | Yes |  |
| `resource_group` | string | Yes |  |
| `resource_type` | [mcn_resource_type](mcn-resource-type.md) | Yes |  |
| `sections` | mcn_resource_details_section[] | Yes |  |
| `state` | object | Yes |  |
| `tags` | object | Yes |  |
| `updated_at` | string | Yes |  |
| `url` | string | Yes |  |

