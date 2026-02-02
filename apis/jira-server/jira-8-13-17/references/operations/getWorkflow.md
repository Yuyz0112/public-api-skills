# GET /workflowscheme/{id}/workflow

**Resource:** [workflowscheme](../resources/workflowscheme.md)
**Operation ID:** `getWorkflow`

Returns the workflow mappings or requested mapping to the caller for the passed scheme.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflowName` | query | string | No | the workflow mapping to return. Null can be passed to return all mappings. Must be a valid workflow name. |
| `returnDraftIfExists` | query | boolean | No | when true indicates that a scheme's draft, if it exists, should be queried instead of
                            the scheme itself. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

