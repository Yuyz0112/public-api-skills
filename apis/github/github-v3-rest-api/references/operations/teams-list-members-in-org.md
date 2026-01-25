# GET /orgs/{org}/teams/{team_slug}/members

**Resource:** [teams](../resources/teams.md)
**List team members**
**Operation ID:** `teams/list-members-in-org`

Team members will include the members of child teams.

To list members in a team, the team must be visible to the authenticated user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `role` | query | enum: member, maintainer, all | No | Filters members returned by their role in the team. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [simple-user](../schemas/simple-user/simple-user.md)

