# POST /api/v4/projects/{id}/export

**Resource:** [Project import](../resources/Project-import.md)
**Start export**
**Operation ID:** `postApiV4ProjectsIdExport`

This feature was introduced in GitLab 10.6.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |
| 429 | Too many requests |
| 503 | Service unavailable |

