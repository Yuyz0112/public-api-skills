# DELETE /api/v4/admin/sidekiq/queues/{queue_name}

**Resource:** [admin](../resources/admin.md)
**Drop jobs matching the given metadata from the Sidekiq queue**
**Operation ID:** `deleteApiV4AdminSidekiqQueuesQueueName`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_id` | query | string | No | Metadata key to match |
| `user` | query | string | No | Metadata key to match |
| `user_id` | query | string | No | Metadata key to match |
| `gl_user_id` | query | string | No | Metadata key to match |
| `scoped_user` | query | string | No | Metadata key to match |
| `scoped_user_id` | query | string | No | Metadata key to match |
| `project` | query | string | No | Metadata key to match |
| `root_namespace` | query | string | No | Metadata key to match |
| `client_id` | query | string | No | Metadata key to match |
| `caller_id` | query | string | No | Metadata key to match |
| `remote_ip` | query | string | No | Metadata key to match |
| `job_id` | query | string | No | Metadata key to match |
| `pipeline_id` | query | string | No | Metadata key to match |
| `related_class` | query | string | No | Metadata key to match |
| `feature_category` | query | string | No | Metadata key to match |
| `artifact_size` | query | string | No | Metadata key to match |
| `artifact_used_cdn` | query | string | No | Metadata key to match |
| `artifacts_dependencies_size` | query | string | No | Metadata key to match |
| `artifacts_dependencies_count` | query | string | No | Metadata key to match |
| `root_caller_id` | query | string | No | Metadata key to match |
| `merge_action_status` | query | string | No | Metadata key to match |
| `bulk_import_entity_id` | query | string | No | Metadata key to match |
| `sidekiq_destination_shard_redis` | query | string | No | Metadata key to match |
| `kubernetes_agent_id` | query | string | No | Metadata key to match |
| `subscription_plan` | query | string | No | Metadata key to match |
| `ai_resource` | query | string | No | Metadata key to match |
| `policy_sync_config_id` | query | string | No | Metadata key to match |
| `worker_class` | query | string | No | Metadata key to match |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

