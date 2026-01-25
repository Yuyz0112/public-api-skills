# GET /repos/{owner}/{repo}/forks

**Resource:** [repos](../resources/repos.md)
**List forks**
**Operation ID:** `repos/list-forks`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `sort` | query | enum: newest, oldest, stargazers... | No | The sort order. `stargazers` will sort by star count. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 400 | (reference) |

**Success Response Schema:**

Array of [minimal-repository](../schemas/minimal-repository/minimal-repository.md)

