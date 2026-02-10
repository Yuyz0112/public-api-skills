# POST /api/v4/projects/{id}/merge_requests/{merge_request_iid}/pipelines

**Resource:** [Merge requests](../resources/Merge-requests.md)
**Create merge request pipeline**
**Operation ID:** `postApiV4ProjectsIdMergeRequestsMergeRequestIidPipelines`

Create a new pipeline for a merge request. A pipeline created via this endpoint doesn’t run a regular branch/tag pipeline. It requires `.gitlab-ci.yml` to be configured with `only: [merge_requests]` to create jobs.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad request |
| 404 | Not found |
| 405 | Method not allowed |

**Success Response Schema:**

[APIEntitiesCiPipeline](../schemas/APIEntitiesCiPipeline/APIEntitiesCiPipeline.md)

