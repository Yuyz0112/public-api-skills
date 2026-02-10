# GET /api/v4/groups/{id}/badges/{badge_id}

**Resource:** [Badges](../resources/Badges.md)
**Gets a badge of a group.**
**Operation ID:** `getApiV4GroupsIdBadgesBadgeId`

This feature was introduced in GitLab 10.6.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID or URL-encoded path of the group owned by the authenticated user. |
| `badge_id` | path | integer | Yes | The badge ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesBadge](../schemas/APIEntitiesBadge/APIEntitiesBadge.md)

