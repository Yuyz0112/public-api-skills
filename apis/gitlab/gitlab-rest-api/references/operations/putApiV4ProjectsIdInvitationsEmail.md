# PUT /api/v4/projects/{id}/invitations/{email}

**Resource:** [Invitations](../resources/Invitations.md)
**Updates a group or project invitation.**
**Operation ID:** `putApiV4ProjectsIdInvitationsEmail`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The project ID |
| `email` | path | string | Yes | The email address of the invitation |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesInvitation](../schemas/APIEntitiesInvitation/APIEntitiesInvitation.md)

