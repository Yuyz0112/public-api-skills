# POST /api/v4/projects/{id}/housekeeping

**Resource:** [Projects](../resources/Projects.md)
**Start the housekeeping task for a project**
**Operation ID:** `postApiV4ProjectsIdHousekeeping`

This feature was introduced in GitLab 9.0.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | Unauthorized |
| 403 | Unauthenticated |
| 409 | Conflict |

