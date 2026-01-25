# GET /workflows.stepFailed

**Resource:** [workflows](../resources/workflows.md)
**Operation ID:** `workflows_stepFailed`

Indicate that an app's step in a workflow failed to execute.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `workflow.steps:execute` |
| `workflow_step_execute_id` | query | string | Yes | Context identifier that maps to the correct workflow step execution. |
| `error` | query | string | Yes | A JSON-based object with a `message` property that should contain a human readable error message. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: workflow.steps:execute
