# DELETE /project/{projectKeyOrId}/priorityscheme/{schemeId}

**Resource:** [project](../resources/project.md)
**Operation ID:** `unassignPriorityScheme`

Unassigns project from priority scheme.

 Operation will fail for defualt priority scheme, project is not found or project is not associated with provided priority scheme.

 All project keys associated with the priority scheme will only be returned if additional query parameter is provided <code>expand=projectKeys</code>.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

