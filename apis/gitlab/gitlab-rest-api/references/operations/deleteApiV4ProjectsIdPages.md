# DELETE /api/v4/projects/{id}/pages

**Resource:** [Gitlab pages](../resources/Gitlab-pages.md)
**Unpublish pages**
**Operation ID:** `deleteApiV4ProjectsIdPages`

Remove pages. The user must have administrator access. This feature was introduced in GitLab 12.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 401 | Unauthorized |
| 404 | Not Found |

