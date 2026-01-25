# POST /teams

**Resource:** [Teams](../resources/Teams.md)
**Create a team**
**Operation ID:** `createTeam`

Create a new Team.

A team is a collection of Users and Escalation Policies that represent a group of people within an organization.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#teams)

Scoped OAuth requires: `teams.write`


## Request Body

The team to be created.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | The team that was created. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

