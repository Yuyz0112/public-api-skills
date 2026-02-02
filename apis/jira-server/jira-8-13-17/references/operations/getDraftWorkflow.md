# GET /workflowscheme/{id}/draft/workflow

**Resource:** [workflowscheme](../resources/workflowscheme.md)
**Operation ID:** `getDraftWorkflow`

Returns the draft workflow mappings or requested mapping to the caller.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflowName` | query | string | No | the workflow mapping to return. Null can be passed to return all mappings. Must be a valid workflow name. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

