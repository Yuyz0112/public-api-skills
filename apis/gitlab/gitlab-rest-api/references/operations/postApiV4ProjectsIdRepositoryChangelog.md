# POST /api/v4/projects/{id}/repository/changelog

**Resource:** [Repositories](../resources/Repositories.md)
**Generates a changelog section for a release and commits it in a changelog file**
**Operation ID:** `postApiV4ProjectsIdRepositoryChangelog`

This feature was introduced in GitLab 13.9

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

