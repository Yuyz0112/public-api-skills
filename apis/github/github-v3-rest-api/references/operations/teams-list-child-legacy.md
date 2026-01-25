# GET /teams/{team_id}/teams

**Resource:** [teams](../resources/teams.md)
**List child teams (Legacy)**
**Operation ID:** `teams/list-child-legacy`
⚠️ **Deprecated**

> [!WARNING]
> **Endpoint closing down notice:** This endpoint route is closing down and will be removed from the Teams API. We recommend migrating your existing code to use the new [`List child teams`](https://docs.github.com/rest/teams/teams#list-child-teams) endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | if child teams exist |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

Array of [team](../schemas/team/team.md)

