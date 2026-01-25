# PATCH /enterprises/{enterprise}/teams/{team_slug}

**Resource:** [enterprise-teams](../resources/enterprise-teams.md)
**Update an enterprise team**
**Operation ID:** `enterprise-teams/update`

To edit a team, the authenticated user must be an enterprise owner.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |

**Success Response Schema:**

[enterprise-team](../schemas/enterprise-team/enterprise-team.md)

