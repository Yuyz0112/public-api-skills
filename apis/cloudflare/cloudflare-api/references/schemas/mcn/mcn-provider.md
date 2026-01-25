# mcn_provider

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `aws_arn` | string | No |  |
| `azure_subscription_id` | string | No |  |
| `azure_tenant_id` | string | No |  |
| `cloud_type` | [mcn_cloud_type](mcn-cloud-type.md) | Yes |  |
| `description` | string | No |  |
| `friendly_name` | string | Yes |  |
| `gcp_project_id` | string | No |  |
| `gcp_service_account_email` | string | No |  |
| `id` | [mcn_provider_id](mcn-provider-id.md) | Yes |  |
| `last_updated` | string | Yes |  |
| `lifecycle_state` | [mcn_provider_lifecycle_state](mcn-provider-lifecycle-state.md) | Yes |  |
| `state` | [mcn_provider_discovery_status](mcn-provider-discovery-status.md) | Yes |  |
| `state_v2` | [mcn_provider_discovery_status](mcn-provider-discovery-status.md) | Yes |  |
| `status` | [mcn_provider_status](mcn-provider-status.md) | No |  |

