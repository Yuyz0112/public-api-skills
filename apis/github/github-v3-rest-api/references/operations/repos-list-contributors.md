# GET /repos/{owner}/{repo}/contributors

**Resource:** [repos](../resources/repos.md)
**List repository contributors**
**Operation ID:** `repos/list-contributors`

Lists contributors to the specified repository and sorts them by the number of commits per contributor in descending order. This endpoint may return information that is a few hours old because the GitHub REST API caches contributor data to improve performance.

GitHub identifies contributors by author email address. This endpoint groups contribution counts by GitHub user, which includes all associated email addresses. To improve performance, only the first 500 author email addresses in the repository link to GitHub users. The rest will appear as anonymous contributors without associated GitHub user information.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `anon` | query | string | No | Set to `1` or `true` to include anonymous contributors in results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | If repository contains content |
| 204 | Response if repository is empty |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [contributor](../schemas/contributor/contributor.md)

