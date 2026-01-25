# PUT /orgs/{org}/dependabot/secrets/{secret_name}

**Resource:** [dependabot](../resources/dependabot.md)
**Create or update an organization secret**
**Operation ID:** `dependabot/create-or-update-org-secret`

Creates or updates an organization secret with an encrypted value. Encrypt your secret using
[LibSodium](https://libsodium.gitbook.io/doc/bindings_for_other_languages). For more information, see "[Encrypting secrets for the REST API](https://docs.github.com/rest/guides/encrypting-secrets-for-the-rest-api)."

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

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

