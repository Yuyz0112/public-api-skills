# GET /repos/{owner}/{repo}/collaborators/{username}

**Resource:** [repos](../resources/repos.md)
**Check if a user is a repository collaborator**
**Operation ID:** `repos/check-collaborator`

For organization-owned repositories, the list of collaborators includes outside collaborators, organization members that are direct collaborators, organization members with access through team memberships, organization members with access through default organization permissions, and organization owners.

Team members will include the members of child teams.

The authenticated user must have push access to the repository to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `read:org` and `repo` scopes to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response if user is a collaborator |
| 404 | Not Found if user is not a collaborator |

