# GET /api/v4/projects/{id}/external_status_checks

**Resource:** [External status checks](../resources/External-status-checks.md)
**Get project external status checks**
**Operation ID:** `getApiV4ProjectsIdExternalStatusChecks`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesExternalStatusCheck](../schemas/APIEntitiesExternalStatusCheck/APIEntitiesExternalStatusCheck.md)

