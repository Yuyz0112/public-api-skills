# GET /repos/{owner}/{repo}/actions/secrets/public-key

**Resource:** [actions](../resources/actions.md)
**Get a repository public key**
**Operation ID:** `actions/get-repo-public-key`

Gets your public key, which you need to encrypt secrets. You need to
encrypt a secret before you can create or update secrets.

Anyone with read access to the repository can use this endpoint.

If the repository is private, OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[actions-public-key](../schemas/actions-public-key/actions-public-key.md)

