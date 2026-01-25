# DELETE /repos/{owner}/{repo}

**Resource:** [repos](../resources/repos.md)
**Delete a repository**
**Operation ID:** `repos/delete`

Deleting a repository requires admin access.

If an organization owner has configured the organization to prevent members from deleting organization-owned
repositories, you will get a `403 Forbidden` response.

OAuth app tokens and personal access tokens (classic) need the `delete_repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 307 | (reference) |
| 403 | If an organization owner has configured the organization to prevent members from deleting organization-owned repositories, a member will get this response: |
| 404 | (reference) |
| 409 | (reference) |

