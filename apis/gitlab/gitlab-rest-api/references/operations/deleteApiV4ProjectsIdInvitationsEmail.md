# DELETE /api/v4/projects/{id}/invitations/{email}

**Resource:** [Invitations](../resources/Invitations.md)
**Removes an invitation from a group or project.**
**Operation ID:** `deleteApiV4ProjectsIdInvitationsEmail`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The project ID |
| `email` | path | string | Yes | The email address of the invitation |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 403 | Forbidden |
| 404 | Not found |
| 409 | Could not delete invitation |

