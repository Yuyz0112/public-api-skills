# DELETE /repos/{owner}/{repo}/dependabot/secrets/{secret_name}

**Resource:** [dependabot](../resources/dependabot.md)
**Delete a repository secret**
**Operation ID:** `dependabot/delete-repo-secret`

Deletes a secret in a repository using the secret name.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

