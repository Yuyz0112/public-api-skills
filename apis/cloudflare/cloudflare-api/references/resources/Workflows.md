# Workflows

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/workflows` | List all Workflows | [View](../operations/wor-list-workflows.md) |
| GET | `/accounts/{account_id}/workflows/{workflow_name}` | Get Workflow details | [View](../operations/wor-get-workflow-details.md) |
| PUT | `/accounts/{account_id}/workflows/{workflow_name}` | Create/modify Workflow | [View](../operations/wor-create-or-modify-workflow.md) |
| DELETE | `/accounts/{account_id}/workflows/{workflow_name}` | Deletes a Workflow | [View](../operations/wor-delete-workflow.md) |
| GET | `/accounts/{account_id}/workflows/{workflow_name}/instances` | List of workflow instances | [View](../operations/wor-list-workflow-instances.md) |
| POST | `/accounts/{account_id}/workflows/{workflow_name}/instances` | Create a new workflow instance | [View](../operations/wor-create-new-workflow-instance.md) |
| POST | `/accounts/{account_id}/workflows/{workflow_name}/instances/batch` | Batch create new Workflow instances | [View](../operations/wor-batch-create-workflow-instance.md) |
| POST | `/accounts/{account_id}/workflows/{workflow_name}/instances/batch/terminate` | Batch terminate instances of a workflow | [View](../operations/wor-batch-terminate-workflow-instances.md) |
| GET | `/accounts/{account_id}/workflows/{workflow_name}/instances/terminate` | Get status of the job responsible for terminate all instances of a workflow | [View](../operations/wor-status-terminate-workflow-instances.md) |
| GET | `/accounts/{account_id}/workflows/{workflow_name}/instances/{instance_id}` | Get logs and status from instance | [View](../operations/wor-describe-workflow-instance.md) |
| POST | `/accounts/{account_id}/workflows/{workflow_name}/instances/{instance_id}/events/{event_type}` | Send event to instance | [View](../operations/wor-send-event-workflow-instance.md) |
| PATCH | `/accounts/{account_id}/workflows/{workflow_name}/instances/{instance_id}/status` | Change status of instance | [View](../operations/wor-change-status-workflow-instance.md) |
| GET | `/accounts/{account_id}/workflows/{workflow_name}/versions` | List deployed Workflow versions | [View](../operations/wor-list-workflow-versions.md) |
| GET | `/accounts/{account_id}/workflows/{workflow_name}/versions/{version_id}` | Get Workflow version details | [View](../operations/wor-describe-workflow-versions.md) |
