# PUT /repos/{owner}/{repo}/actions/secrets/{secret_name}

**Resource:** [actions](../resources/actions.md)
**Create or update a repository secret**
**Operation ID:** `actions/create-or-update-repo-secret`

Creates or updates a repository secret with an encrypted value. Encrypt your secret using
[LibSodium](https://libsodium.gitbook.io/doc/bindings_for_other_languages). For more information, see "[Encrypting secrets for the REST API](https://docs.github.com/rest/guides/encrypting-secrets-for-the-rest-api)."

Authenticated users must have collaborator access to a repository to create, update, or read secrets.

OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response when creating a secret |
| 204 | Response when updating a secret |

**Success Response Schema:**

[empty-object](../schemas/empty-object/empty-object.md)

