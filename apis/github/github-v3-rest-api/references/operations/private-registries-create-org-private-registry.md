# POST /orgs/{org}/private-registries

**Resource:** [private-registries](../resources/private-registries.md)
**Create a private registry for an organization**
**Operation ID:** `private-registries/create-org-private-registry`


Creates a private registry configuration with an encrypted value for an organization. Encrypt your secret using [LibSodium](https://libsodium.gitbook.io/doc/bindings_for_other_languages). For more information, see "[Encrypting secrets for the REST API](https://docs.github.com/rest/guides/encrypting-secrets-for-the-rest-api)."

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | The organization private registry configuration |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[org-private-registry-configuration-with-selected-repositories](../schemas/org-private-registry-configuration-with-selected-repositories/org-private-registry-configuration-with-selected-repositories.md)

