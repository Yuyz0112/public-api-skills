# GET /workflow/transitions/{id}/properties

**Resource:** [workflow](../resources/workflow.md)
**Operation ID:** `getProperties`

Return the property or properties associated with a transition.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `includeReservedKeys` | query | boolean | No | some keys under the "jira." prefix are editable, some are not. Set this to true
                            in order to include the non-editable keys in the response. |
| `key` | query | string | No | the name of the property key to query. Can be left off the query to return all properties. |
| `workflowName` | query | string | No | the name of the workflow to use. |
| `workflowMode` | query | string | No | the type of workflow to use. Can either be "live" or "draft". |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

