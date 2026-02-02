# DELETE /workflowscheme/{id}/workflow

**Resource:** [workflowscheme](../resources/workflowscheme.md)
**Operation ID:** `deleteWorkflowMapping`

Delete the passed workflow from the workflow scheme.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflowName` | query | string | No | the name of the workflow to delete. |
| `updateDraftIfNeeded` | query | boolean | No | flag to indicate if a draft should be created if necessary to delete the workflow
                            from the scheme. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

