# GET /api/v4/groups/{id}/badges/render

**Resource:** [Badges](../resources/Badges.md)
**Preview a badge from a group.**
**Operation ID:** `getApiV4GroupsIdBadgesRender`

This feature was introduced in GitLab 10.6.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID or URL-encoded path of the group owned by the authenticated user. |
| `link_url` | query | string | Yes | URL of the badge link |
| `image_url` | query | string | Yes | URL of the badge image |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesBasicBadgeDetails](../schemas/APIEntitiesBasicBadgeDetails/APIEntitiesBasicBadgeDetails.md)

