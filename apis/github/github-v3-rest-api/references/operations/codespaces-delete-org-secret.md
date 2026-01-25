# DELETE /orgs/{org}/codespaces/secrets/{secret_name}

**Resource:** [codespaces](../resources/codespaces.md)
**Delete an organization secret**
**Operation ID:** `codespaces/delete-org-secret`

Deletes an organization development environment secret using the secret name.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 404 | (reference) |

