# PUT /project/{projectIdOrKey}

**Resource:** [project](../resources/project.md)
**Operation ID:** `updateProject`

Updates a project.
 <p>
 Only non null values sent in JSON will be updated in the project.</p>
 <p>
 Values available for the assigneeType field are: "PROJECT_LEAD" and "UNASSIGNED".</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string | No | the parameters to expand in returned project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

