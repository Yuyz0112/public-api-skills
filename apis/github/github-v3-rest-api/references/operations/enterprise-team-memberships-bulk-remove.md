# POST /enterprises/{enterprise}/teams/{enterprise-team}/memberships/remove

**Resource:** [enterprise-team-memberships](../resources/enterprise-team-memberships.md)
**Bulk remove team members**
**Operation ID:** `enterprise-team-memberships/bulk-remove`

Remove multiple team members from an enterprise team.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully removed team members. |

**Success Response Schema:**

Array of [simple-user](../schemas/simple-user/simple-user.md)

