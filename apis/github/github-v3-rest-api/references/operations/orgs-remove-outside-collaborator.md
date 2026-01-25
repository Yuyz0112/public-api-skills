# DELETE /orgs/{org}/outside_collaborators/{username}

**Resource:** [orgs](../resources/orgs.md)
**Remove outside collaborator from an organization**
**Operation ID:** `orgs/remove-outside-collaborator`

Removing a user from this list will remove them from all the organization's repositories.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 422 | Unprocessable Entity if user is a member of the organization |

