# GET /api/v4/analytics/group_activity/new_members_count

**Resource:** [Analytics](../resources/Analytics.md)
**Get count of recently created group members**
**Operation ID:** `getApiV4AnalyticsGroupActivityNewMembersCount`

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

[APIEntitiesAnalyticsGroupActivityNewMembersCount](../schemas/APIEntitiesAnalyticsGroupActivityNewMembersCount/APIEntitiesAnalyticsGroupActivityNewMembersCount.md)

