# GET /api/v4/projects/{id}/releases/{tag_name}/assets/links/{link_id}

**Resource:** [Releases](../resources/Releases.md)
**Get a release link**
**Operation ID:** `getApiV4ProjectsIdReleasesTagNameAssetsLinksLinkId`

Get an asset as a link from a release. This feature was introduced in GitLab 11.7.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `tag_name` | path | string | Yes | The tag associated with the release |
| `link_id` | path | integer | Yes | The ID of the link |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesReleasesLink](../schemas/APIEntitiesReleasesLink/APIEntitiesReleasesLink.md)

