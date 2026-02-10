# POST /api/v4/projects/{id}/environments/stop_stale

**Resource:** [Environments](../resources/Environments.md)
**Stop stale environments**
**Operation ID:** `postApiV4ProjectsIdEnvironmentsStopStale`

It returns `200` if stale environment check was scheduled successfully

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 400 | Bad request |
| 401 | Unauthorized |

