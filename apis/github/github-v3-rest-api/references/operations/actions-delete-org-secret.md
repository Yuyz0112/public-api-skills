# DELETE /orgs/{org}/actions/secrets/{secret_name}

**Resource:** [actions](../resources/actions.md)
**Delete an organization secret**
**Operation ID:** `actions/delete-org-secret`

Deletes a secret in an organization using the secret name.

Authenticated users must have collaborator access to a repository to create, update, or read secrets.

OAuth tokens and personal access tokens (classic) need the`admin:org` scope to use this endpoint. If the repository is private, OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

