# PATCH /orgs/{org}/teams/{team_slug}

**Resource:** [teams](../resources/teams.md)
**Update a team**
**Operation ID:** `teams/update-in-org`

To edit a team, the authenticated user must either be an organization owner or a team maintainer.

> [!NOTE]
> You can also specify a team by `org_id` and `team_id` using the route `PATCH /organizations/{org_id}/team/{team_id}`.

## Request Body

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

