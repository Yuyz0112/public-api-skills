# GET /repos/{owner}/{repo}/dependabot/secrets

**Resource:** [dependabot](../resources/dependabot.md)
**List repository secrets**
**Operation ID:** `dependabot/list-repo-secrets`

Lists all secrets available in a repository without revealing their encrypted
values.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

