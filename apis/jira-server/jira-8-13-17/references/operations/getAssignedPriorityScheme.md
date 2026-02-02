# GET /project/{projectKeyOrId}/priorityscheme

**Resource:** [project](../resources/project.md)
**Operation ID:** `getAssignedPriorityScheme`

Gets a full representation of a priority scheme in JSON format used by specified project.
 User must be global administrator or project administrator.

 All project keys associated with the priority scheme will only be returned if additional query parameter is provided <code>expand=projectKeys</code>.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

