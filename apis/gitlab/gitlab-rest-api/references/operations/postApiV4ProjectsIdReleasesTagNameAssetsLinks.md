# POST /api/v4/projects/{id}/releases/{tag_name}/assets/links

**Resource:** [Releases](../resources/Releases.md)
**Create a release link**
**Operation ID:** `postApiV4ProjectsIdReleasesTagNameAssetsLinks`

Create an asset as a link from a release. This feature was introduced in GitLab 11.7.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `tag_name` | path | string | Yes | The tag associated with the release |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad request |
| 401 | Unauthorized |

**Success Response Schema:**

[APIEntitiesReleasesLink](../schemas/APIEntitiesReleasesLink/APIEntitiesReleasesLink.md)

