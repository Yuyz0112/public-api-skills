# GET /repos/{owner}/{repo}/invitations

**Resource:** [repos](../resources/repos.md)
**List repository invitations**
**Operation ID:** `repos/list-invitations`

When authenticating as a user with admin rights to a repository, this endpoint will list all currently open repository invitations.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [repository-invitation](../schemas/repository-invitation/repository-invitation.md)

