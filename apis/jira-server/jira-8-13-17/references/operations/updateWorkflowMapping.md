# PUT /workflowscheme/{id}/workflow

**Resource:** [workflowscheme](../resources/workflowscheme.md)
**Operation ID:** `updateWorkflowMapping`

Update the scheme to include the passed mapping.
 <p/>
 The body is a representation of the workflow mapping.
 Values not passed are assumed to indicate no change for that field.
 <p/>
 The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft
 should be created/updated when the actual scheme cannot be edited.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflowName` | query | string | No | the name of the workflow mapping to update. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

