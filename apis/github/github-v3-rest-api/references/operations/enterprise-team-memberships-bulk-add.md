# POST /enterprises/{enterprise}/teams/{enterprise-team}/memberships/add

**Resource:** [enterprise-team-memberships](../resources/enterprise-team-memberships.md)
**Bulk add team members**
**Operation ID:** `enterprise-team-memberships/bulk-add`

Add multiple team members to an enterprise team.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully added team members. |

**Success Response Schema:**

Array of [simple-user](../schemas/simple-user/simple-user.md)

