# GET /teams/{team_id}

**Resource:** [teams](../resources/teams.md)
**Get a team (Legacy)**
**Operation ID:** `teams/get-legacy`
⚠️ **Deprecated**

> [!WARNING]
> **Endpoint closing down notice:** This endpoint route is closing down and will be removed from the Teams API. We recommend migrating your existing code to use the [Get a team by name](https://docs.github.com/rest/teams/teams#get-a-team-by-name) endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

[team-full](../schemas/team-full/team-full.md)

