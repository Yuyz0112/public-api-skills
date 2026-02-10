# GET /api/v4/projects/{id}/releases/{tag_name}

**Resource:** [Releases](../resources/Releases.md)
**Get a release by a tag name**
**Operation ID:** `getApiV4ProjectsIdReleasesTagName`

Gets a release for the given tag. This feature was introduced in GitLab 11.7.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `tag_name` | path | string | Yes | The Git tag the release is associated with |
| `include_html_description` | query | boolean | No | If `true`, a response includes HTML rendered markdown of the release description |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesRelease](../schemas/APIEntitiesRelease/APIEntitiesRelease.md)

