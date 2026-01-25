# GET /repos/{owner}/{repo}/codespaces

**Resource:** [codespaces](../resources/codespaces.md)
**List codespaces in a repository for the authenticated user**
**Operation ID:** `codespaces/list-in-repository-for-authenticated-user`

Lists the codespaces associated to a specified repository and the authenticated user.

OAuth app tokens and personal access tokens (classic) need the `codespace` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

