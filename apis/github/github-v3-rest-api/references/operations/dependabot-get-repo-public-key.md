# GET /repos/{owner}/{repo}/dependabot/secrets/public-key

**Resource:** [dependabot](../resources/dependabot.md)
**Get a repository public key**
**Operation ID:** `dependabot/get-repo-public-key`

Gets your public key, which you need to encrypt secrets. You need to
encrypt a secret before you can create or update secrets. Anyone with read access
to the repository can use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint if the repository is private.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[dependabot-public-key](../schemas/dependabot-public-key/dependabot-public-key.md)

