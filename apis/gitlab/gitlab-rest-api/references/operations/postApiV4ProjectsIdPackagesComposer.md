# POST /api/v4/projects/{id}/packages/composer

**Resource:** [Packages](../resources/Packages.md)
**Composer packages endpoint for registering packages**
**Operation ID:** `postApiV4ProjectsIdPackagesComposer`

This feature was introduced in GitLab 13.1

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of a project |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

