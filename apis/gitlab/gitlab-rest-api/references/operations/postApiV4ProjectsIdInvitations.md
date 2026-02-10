# POST /api/v4/projects/{id}/invitations

**Resource:** [Invitations](../resources/Invitations.md)
**Invite non-members by email address to a group or project.**
**Operation ID:** `postApiV4ProjectsIdInvitations`

This feature was introduced in GitLab 13.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The project ID |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesInvitation](../schemas/APIEntitiesInvitation/APIEntitiesInvitation.md)

