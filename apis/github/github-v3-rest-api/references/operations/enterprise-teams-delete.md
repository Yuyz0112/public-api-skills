# DELETE /enterprises/{enterprise}/teams/{team_slug}

**Resource:** [enterprise-teams](../resources/enterprise-teams.md)
**Delete an enterprise team**
**Operation ID:** `enterprise-teams/delete`

To delete an enterprise team, the authenticated user must be an enterprise owner.

If you are an enterprise owner, deleting an enterprise team will delete all of its IdP mappings as well.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 403 | (reference) |

