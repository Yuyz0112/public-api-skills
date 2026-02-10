# DELETE /api/v4/projects/{id}/badges/{badge_id}

**Resource:** [Badges](../resources/Badges.md)
**Removes a badge from the project.**
**Operation ID:** `deleteApiV4ProjectsIdBadgesBadgeId`

This feature was introduced in GitLab 10.6.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID or URL-encoded path of the project owned by the authenticated user. |
| `badge_id` | path | integer | Yes | The badge ID |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

