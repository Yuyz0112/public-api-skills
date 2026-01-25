# DELETE /user/codespaces/secrets/{secret_name}

**Resource:** [codespaces](../resources/codespaces.md)
**Delete a secret for the authenticated user**
**Operation ID:** `codespaces/delete-secret-for-authenticated-user`

Deletes a development environment secret from a user's codespaces using the secret name. Deleting the secret will remove access from all codespaces that were allowed to access the secret.

The authenticated user must have Codespaces access to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `codespace` or `codespace:secrets` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

