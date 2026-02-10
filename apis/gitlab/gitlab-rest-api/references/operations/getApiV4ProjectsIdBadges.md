# GET /api/v4/projects/{id}/badges

**Resource:** [Badges](../resources/Badges.md)
**Gets a list of project badges viewable by the authenticated user.**
**Operation ID:** `getApiV4ProjectsIdBadges`

This feature was introduced in GitLab 10.6.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID or URL-encoded path of the project owned by the authenticated user. |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `name` | query | string | No | Name for the badge |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesBadge](../schemas/APIEntitiesBadge/APIEntitiesBadge.md)

