# PUT /project/{projectKeyOrId}/priorityscheme

**Resource:** [project](../resources/project.md)
**Operation ID:** `assignPriorityScheme`

Assigns project with priority scheme.
 Priority scheme assign with migration is possible from the UI.

 Operation will fail if migration is needed as a result of operation eg. there are issues with priorities invalid in the destination scheme.

 All project keys associated with the priority scheme will only be returned if additional query parameter is provided <code>expand=projectKeys</code>.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

