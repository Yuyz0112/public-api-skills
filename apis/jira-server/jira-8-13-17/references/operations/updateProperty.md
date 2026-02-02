# PUT /workflow/transitions/{id}/properties

**Resource:** [workflow](../resources/workflow.md)
**Operation ID:** `updateProperty`

Update/add new property to a transition. Trying to update a property that does
 not exist will result in a new property being added.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key` | query | string | No | the name of the property to add. |
| `workflowName` | query | string | No | the name of the workflow to use. |
| `workflowMode` | query | string | No | the type of workflow to use. Can either be "live" or "draft". |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

