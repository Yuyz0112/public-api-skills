# PUT /user/codespaces/secrets/{secret_name}

**Resource:** [codespaces](../resources/codespaces.md)
**Create or update a secret for the authenticated user**
**Operation ID:** `codespaces/create-or-update-secret-for-authenticated-user`

Creates or updates a development environment secret for a user's codespace with an encrypted value. Encrypt your secret using
[LibSodium](https://libsodium.gitbook.io/doc/bindings_for_other_languages). For more information, see "[Encrypting secrets for the REST API](https://docs.github.com/rest/guides/encrypting-secrets-for-the-rest-api)."

The authenticated user must have Codespaces access to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `codespace` or `codespace:secrets` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response after successfully creating a secret |
| 204 | Response after successfully updating a secret |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[empty-object](../schemas/empty-object/empty-object.md)

