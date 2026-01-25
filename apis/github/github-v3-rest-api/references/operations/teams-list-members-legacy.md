# GET /teams/{team_id}/members

**Resource:** [teams](../resources/teams.md)
**List team members (Legacy)**
**Operation ID:** `teams/list-members-legacy`
⚠️ **Deprecated**

> [!WARNING]
> **Endpoint closing down notice:** This endpoint route is closing down and will be removed from the Teams API. We recommend migrating your existing code to use the new [`List team members`](https://docs.github.com/rest/teams/members#list-team-members) endpoint.

Team members will include the members of child teams.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `role` | query | enum: member, maintainer, all | No | Filters members returned by their role in the team. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

Array of [simple-user](../schemas/simple-user/simple-user.md)

