# mcn_provider_status

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `credentials_good_since` | string | No |  |
| `credentials_missing_since` | string | No |  |
| `credentials_rejected_since` | string | No |  |
| `discovery_message` | string | No |  |
| `discovery_message_v2` | string | No |  |
| `discovery_progress` | [mcn_provider_discovery_progress](mcn-provider-discovery-progress.md) | Yes |  |
| `discovery_progress_v2` | [mcn_provider_discovery_progress](mcn-provider-discovery-progress.md) | Yes |  |
| `in_use_by` | mcn_cloud_platform_client[] | No |  |
| `last_discovery_completed_at` | string | No |  |
| `last_discovery_completed_at_v2` | string | No |  |
| `last_discovery_started_at` | string | No |  |
| `last_discovery_started_at_v2` | string | No |  |
| `last_discovery_status` | [mcn_provider_discovery_status](mcn-provider-discovery-status.md) | Yes |  |
| `last_discovery_status_v2` | [mcn_provider_discovery_status](mcn-provider-discovery-status.md) | Yes |  |
| `last_updated` | string | No |  |
| `regions` | string[] | Yes |  |

