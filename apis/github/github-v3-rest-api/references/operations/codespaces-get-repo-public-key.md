# GET /repos/{owner}/{repo}/codespaces/secrets/public-key

**Resource:** [codespaces](../resources/codespaces.md)
**Get a repository public key**
**Operation ID:** `codespaces/get-repo-public-key`

Gets your public key, which you need to encrypt secrets. You need to
encrypt a secret before you can create or update secrets.

If the repository is private, OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[codespaces-public-key](../schemas/codespaces-public-key/codespaces-public-key.md)

