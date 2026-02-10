# POST /api/v4/groups/{id}/badges

**Resource:** [Badges](../resources/Badges.md)
**Adds a badge to a group.**
**Operation ID:** `postApiV4GroupsIdBadges`

This feature was introduced in GitLab 10.6.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID or URL-encoded path of the group owned by the authenticated user. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesBadge](../schemas/APIEntitiesBadge/APIEntitiesBadge.md)

