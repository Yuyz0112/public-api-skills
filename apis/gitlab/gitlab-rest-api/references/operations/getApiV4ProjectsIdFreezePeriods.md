# GET /api/v4/projects/{id}/freeze_periods

**Resource:** [Freeze periods](../resources/Freeze-periods.md)
**List freeze periods**
**Operation ID:** `getApiV4ProjectsIdFreezePeriods`

Paginated list of Freeze Periods, sorted by created_at in ascending order. This feature was introduced in GitLab 13.0.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesFreezePeriod](../schemas/APIEntitiesFreezePeriod/APIEntitiesFreezePeriod.md)

