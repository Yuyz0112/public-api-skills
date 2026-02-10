# GET /api/v4/projects/{id}/jobs

**Resource:** [CI jobs](../resources/CI-jobs.md)
**Get a projects jobs**
**Operation ID:** `getApiV4ProjectsIdJobs`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `scope` | query | any | No | The scope of builds to show |
| `ref` | query | string | No | The branch name (ref) to filter jobs by |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiJob](../schemas/APIEntitiesCiJob/APIEntitiesCiJob.md)

