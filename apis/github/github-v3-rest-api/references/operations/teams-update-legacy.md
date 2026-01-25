# PATCH /teams/{team_id}

**Resource:** [teams](../resources/teams.md)
**Update a team (Legacy)**
**Operation ID:** `teams/update-legacy`
⚠️ **Deprecated**

> [!WARNING]
> **Endpoint closing down notice:** This endpoint route is closing down and will be removed from the Teams API. We recommend migrating your existing code to use the new [Update a team](https://docs.github.com/rest/teams/teams#update-a-team) endpoint.

To edit a team, the authenticated user must either be an organization owner or a team maintainer.

> [!NOTE]
> With nested teams, the `privacy` for parent teams cannot be `secret`.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response when the updated information already exists |
| 201 | Response |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[team-full](../schemas/team-full/team-full.md)

