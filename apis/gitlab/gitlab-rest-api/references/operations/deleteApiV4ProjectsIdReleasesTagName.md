# DELETE /api/v4/projects/{id}/releases/{tag_name}

**Resource:** [Releases](../resources/Releases.md)
**Delete a release**
**Operation ID:** `deleteApiV4ProjectsIdReleasesTagName`

Delete a release. Deleting a release doesn't delete the associated tag. Maintainer level access to the project is required to delete a release. This feature was introduced in GitLab 11.7.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `tag_name` | path | string | Yes | The Git tag the release is associated with |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

