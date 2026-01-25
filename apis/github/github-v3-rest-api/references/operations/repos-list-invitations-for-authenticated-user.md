# GET /user/repository_invitations

**Resource:** [repos](../resources/repos.md)
**List repository invitations for the authenticated user**
**Operation ID:** `repos/list-invitations-for-authenticated-user`

When authenticating as a user, this endpoint will list all currently open repository invitations for that user.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [repository-invitation](../schemas/repository-invitation/repository-invitation.md)

