# GET /teams/{team_id}/repos

**Resource:** [teams](../resources/teams.md)
**List team repositories (Legacy)**
**Operation ID:** `teams/list-repos-legacy`
⚠️ **Deprecated**

> [!WARNING]
> **Endpoint closing down notice:** This endpoint route is closing down and will be removed from the Teams API. We recommend migrating your existing code to use the new [List team repositories](https://docs.github.com/rest/teams/teams#list-team-repositories) endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

Array of [minimal-repository](../schemas/minimal-repository/minimal-repository.md)

