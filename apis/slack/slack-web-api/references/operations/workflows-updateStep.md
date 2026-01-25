# GET /workflows.updateStep

**Resource:** [workflows](../resources/workflows.md)
**Operation ID:** `workflows_updateStep`

Update the configuration for a workflow extension step.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `workflow.steps:execute` |
| `workflow_step_edit_id` | query | string | Yes | A context identifier provided with `view_submission` payloads used to call back to `workflows.updateStep`. |
| `inputs` | query | string | No | A JSON key-value map of inputs required from a user during configuration. This is the data your app expects to receive when the workflow step starts. **Please note**: the embedded variable format is set and replaced by the workflow system. You cannot create custom variables that will be replaced at runtime. [Read more about variables in workflow steps here](/workflows/steps#variables). |
| `outputs` | query | string | No | An JSON array of output objects used during step execution. This is the data your app agrees to provide when your workflow step was executed. |
| `step_name` | query | string | No | An optional field that can be used to override the step name that is shown in the Workflow Builder. |
| `step_image_url` | query | string | No | An optional field that can be used to override app image that is shown in the Workflow Builder. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: workflow.steps:execute
