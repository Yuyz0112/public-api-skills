# GET /api/v4/projects/{id}/analytics/deployment_frequency

**Resource:** [Analytics](../resources/Analytics.md)
**List deployment frequencies for the project**
**Operation ID:** `getApiV4ProjectsIdAnalyticsDeploymentFrequency`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `environment` | query | string | Yes | Name of the environment to filter by |
| `from` | query | string (date-time) | Yes | Datetime to start from, inclusive |
| `to` | query | string (date-time) | No | Datetime to end at, exclusive |
| `interval` | query | enum: all, monthly, daily | No | Interval to roll-up data by |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesAnalyticsDeploymentFrequency](../schemas/APIEntitiesAnalyticsDeploymentFrequency/APIEntitiesAnalyticsDeploymentFrequency.md)

