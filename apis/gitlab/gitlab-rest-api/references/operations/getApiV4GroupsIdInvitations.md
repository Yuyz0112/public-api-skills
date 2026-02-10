# GET /api/v4/groups/{id}/invitations

**Resource:** [Invitations](../resources/Invitations.md)
**Get a list of group or project invitations viewable by the authenticated user**
**Operation ID:** `getApiV4GroupsIdInvitations`

This feature was introduced in GitLab 13.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The group ID |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `query` | query | string | No | A query string to search for members |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesInvitation](../schemas/APIEntitiesInvitation/APIEntitiesInvitation.md)

