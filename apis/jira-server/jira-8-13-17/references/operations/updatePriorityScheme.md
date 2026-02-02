# PUT /priorityschemes/{schemeId}

**Resource:** [priorityschemes](../resources/priorityschemes.md)
**Operation ID:** `updatePriorityScheme`

Updates a priority scheme.
 Update will be rejected if issue migration would be needed as a result of scheme update.
 Priority scheme update with migration is possible from the UI.

 All project keys associated with the priority scheme will only be returned if additional query parameter is provided <code>expand=projectKeys</code>.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

