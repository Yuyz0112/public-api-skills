# DELETE /repos/{owner}/{repo}/autolinks/{autolink_id}

**Resource:** [repos](../resources/repos.md)
**Delete an autolink reference from a repository**
**Operation ID:** `repos/delete-autolink`

This deletes a single autolink reference by ID that was configured for the given repository.

Information about autolinks are only available to repository administrators.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 404 | (reference) |

