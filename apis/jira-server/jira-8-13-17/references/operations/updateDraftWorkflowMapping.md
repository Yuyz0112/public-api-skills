# PUT /workflowscheme/{id}/draft/workflow

**Resource:** [workflowscheme](../resources/workflowscheme.md)
**Operation ID:** `updateDraftWorkflowMapping`

Update the draft scheme to include the passed mapping.
 <p/>
 The body is a representation of the workflow mapping.
 Values not passed are assumed to indicate no change for that field.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflowName` | query | string | No | the name of the workflow mapping to update. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

