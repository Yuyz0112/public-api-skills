# DELETE /api/v4/projects/{id}/releases/{tag_name}/assets/links/{link_id}

**Resource:** [Releases](../resources/Releases.md)
**Delete a release link**
**Operation ID:** `deleteApiV4ProjectsIdReleasesTagNameAssetsLinksLinkId`

Deletes an asset as a link from a release. This feature was introduced in GitLab 11.7.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `tag_name` | path | string | Yes | The tag associated with the release |
| `link_id` | path | integer | Yes | The ID of the link |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad request |
| 401 | Unauthorized |

