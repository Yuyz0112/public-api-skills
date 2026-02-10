# POST /api/v4/projects/{id}/freeze_periods

**Resource:** [Freeze periods](../resources/Freeze-periods.md)
**Create a freeze period**
**Operation ID:** `postApiV4ProjectsIdFreezePeriods`

Creates a freeze period. This feature was introduced in GitLab 13.0.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad request |
| 401 | Unauthorized |

**Success Response Schema:**

[APIEntitiesFreezePeriod](../schemas/APIEntitiesFreezePeriod/APIEntitiesFreezePeriod.md)

