# GET /api/v4/projects/{id}/pages

**Resource:** [Gitlab pages](../resources/Gitlab-pages.md)
**Get pages settings**
**Operation ID:** `getApiV4ProjectsIdPages`

Get pages URL and other settings. This feature was introduced in Gitlab 16.8

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not Found |

