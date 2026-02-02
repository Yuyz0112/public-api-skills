# GET /workflowscheme/{id}/default

**Resource:** [workflowscheme](../resources/workflowscheme.md)
**Operation ID:** `getDefault`

Return the default workflow from the passed workflow scheme.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `returnDraftIfExists` | query | boolean | No | when true indicates that a scheme's draft, if it exists, should be queried instead of
                            the scheme itself. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

