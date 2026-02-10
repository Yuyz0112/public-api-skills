# GET /api/v4/runners/{id}/jobs

**Resource:** [Jobs](../resources/Jobs.md)
**List jobs running on a runner**
**Operation ID:** `getApiV4RunnersIdJobs`

List jobs that are being processed or were processed by the specified runner. The list of jobs is limited to projects where the user has at least the Reporter role.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of a runner |
| `system_id` | query | string | No | System ID associated with the runner manager |
| `status` | query | enum: created, waiting_for_resource, preparing... | No | Status of the job |
| `order_by` | query | enum: id | No | Order by `id` |
| `sort` | query | enum: asc, desc | No | Sort by `asc` or `desc` order. Specify `order_by` as well, including for `id` |
| `cursor` | query | string | No | Cursor for obtaining the next set of records |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | No access granted |
| 404 | Runner not found |

**Success Response Schema:**

[APIEntitiesCiJobBasicWithProject](../schemas/APIEntitiesCiJobBasicWithProject/APIEntitiesCiJobBasicWithProject.md)

