# POST /workflow/transitions/{id}/properties

**Resource:** [workflow](../resources/workflow.md)
**Operation ID:** `createProperty`

Add a new property to a transition. Trying to add a property that already
 exists will fail.

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

