# DELETE /repos/{owner}/{repo}/hooks/{hook_id}

**Resource:** [repos](../resources/repos.md)
**Delete a repository webhook**
**Operation ID:** `repos/delete-webhook`

Delete a webhook for an organization.

The authenticated user must be a repository owner, or have admin access in the repository, to delete the webhook.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 404 | (reference) |

