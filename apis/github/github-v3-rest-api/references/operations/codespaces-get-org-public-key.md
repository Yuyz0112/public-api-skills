# GET /orgs/{org}/codespaces/secrets/public-key

**Resource:** [codespaces](../resources/codespaces.md)
**Get an organization public key**
**Operation ID:** `codespaces/get-org-public-key`

Gets a public key for an organization, which is required in order to encrypt secrets. You need to encrypt the value of a secret before you can create or update secrets.
OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[codespaces-public-key](../schemas/codespaces-public-key/codespaces-public-key.md)

