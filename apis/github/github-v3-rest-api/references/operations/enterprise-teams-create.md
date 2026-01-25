# POST /enterprises/{enterprise}/teams

**Resource:** [enterprise-teams](../resources/enterprise-teams.md)
**Create an enterprise team**
**Operation ID:** `enterprise-teams/create`

To create an enterprise team, the authenticated user must be an owner of the enterprise.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |

**Success Response Schema:**

[enterprise-team](../schemas/enterprise-team/enterprise-team.md)

