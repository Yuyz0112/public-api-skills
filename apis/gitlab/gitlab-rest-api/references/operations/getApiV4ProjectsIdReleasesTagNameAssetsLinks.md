# GET /api/v4/projects/{id}/releases/{tag_name}/assets/links

**Resource:** [Releases](../resources/Releases.md)
**List links of a release**
**Operation ID:** `getApiV4ProjectsIdReleasesTagNameAssetsLinks`

Get assets as links from a release. This feature was introduced in GitLab 11.7.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `tag_name` | path | string | Yes | The tag associated with the release |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesReleasesLink](../schemas/APIEntitiesReleasesLink/APIEntitiesReleasesLink.md)

