# GET /api/v4/analytics/group_activity/issues_count

**Resource:** [Analytics](../resources/Analytics.md)
**Get count of recently created issues for the group**
**Operation ID:** `getApiV4AnalyticsGroupActivityIssuesCount`

This feature was introduced in GitLab 12.9.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `group_path` | query | string | Yes | Group path |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesAnalyticsGroupActivityIssuesCount](../schemas/APIEntitiesAnalyticsGroupActivityIssuesCount/APIEntitiesAnalyticsGroupActivityIssuesCount.md)

