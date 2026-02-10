# GET /api/v4/analytics/group_activity/merge_requests_count

**Resource:** [Analytics](../resources/Analytics.md)
**Get count of recently created merge requests for the group**
**Operation ID:** `getApiV4AnalyticsGroupActivityMergeRequestsCount`

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

[APIEntitiesAnalyticsGroupActivityMergeRequestsCount](../schemas/APIEntitiesAnalyticsGroupActivityMergeRequestsCount/APIEntitiesAnalyticsGroupActivityMergeRequestsCount.md)

