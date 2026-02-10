# POST /api/v4/projects/{id}/badges

**Resource:** [Badges](../resources/Badges.md)
**Adds a badge to a project.**
**Operation ID:** `postApiV4ProjectsIdBadges`

This feature was introduced in GitLab 10.6.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID or URL-encoded path of the project owned by the authenticated user. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesBadge](../schemas/APIEntitiesBadge/APIEntitiesBadge.md)

