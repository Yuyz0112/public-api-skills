# GET /workflows.stepCompleted

**Resource:** [workflows](../resources/workflows.md)
**Operation ID:** `workflows_stepCompleted`

Indicate that an app's step in a workflow completed execution.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `workflow.steps:execute` |
| `workflow_step_execute_id` | query | string | Yes | Context identifier that maps to the correct workflow step execution. |
| `outputs` | query | string | No | Key-value object of outputs from your step. Keys of this object reflect the configured `key` properties of your [`outputs`](/reference/workflows/workflow_step#output) array from your `workflow_step` object. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: workflow.steps:execute
