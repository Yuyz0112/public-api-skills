# GET /teams/{id}/members

**Resource:** [Teams](../resources/Teams.md)
**List members of a team**
**Operation ID:** `listTeamUsers`

Get information about members on a team.

A team is a collection of Users and Escalation Policies that represent a group of people within an organization.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#teams)

Scoped OAuth requires: `teams.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A paginated array of users within the requested team. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

