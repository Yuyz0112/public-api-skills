# PUT /teams/{id}/users/{user_id}

**Resource:** [Teams](../resources/Teams.md)
**Add a user to a team**
**Operation ID:** `updateTeamUser`

Add a user to a team. Attempting to add a user with the `read_only_user` role will return a 400 error.

A team is a collection of Users and Escalation Policies that represent a group of people within an organization.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#teams)

Scoped OAuth requires: `teams.write`


## Request Body

The role of the user on the team.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | The user was added to the team. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

