# DELETE /workflowscheme/{id}/default

**Resource:** [workflowscheme](../resources/workflowscheme.md)
**Operation ID:** `deleteDefault`

Remove the default workflow from the passed workflow scheme.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `updateDraftIfNeeded` | query | boolean | No | when true will create and return a draft when the workflow scheme cannot be edited
                            (e.g. when it is being used by a project). |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

