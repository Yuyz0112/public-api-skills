# GET /repos/{owner}/{repo}/pages/builds/{build_id}

**Resource:** [repos](../resources/repos.md)
**Get GitHub Pages build**
**Operation ID:** `repos/get-pages-build`

Gets information about a GitHub Pages build.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `build_id` | path | integer | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[page-build](../schemas/page-build/page-build.md)

