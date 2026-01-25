# GET /enterprises/{enterprise}/teams/{enterprise-team}/memberships/{username}

**Resource:** [enterprise-team-memberships](../resources/enterprise-team-memberships.md)
**Get enterprise team membership**
**Operation ID:** `enterprise-team-memberships/get`

Returns whether the user is a member of the enterprise team.

## Responses

| Status | Description |
|--------|-------------|
| 200 | User is a member of the enterprise team. |

**Success Response Schema:**

[simple-user](../schemas/simple-user/simple-user.md)

