# PATCH /api/v4/projects/{id}/pages

**Resource:** [Gitlab pages](../resources/Gitlab-pages.md)
**Update pages settings**
**Operation ID:** `patchApiV4ProjectsIdPages`

Update page settings for a project. User must have administrative access.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not Found |

