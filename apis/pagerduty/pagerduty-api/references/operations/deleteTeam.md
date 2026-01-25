# DELETE /teams/{id}

**Resource:** [Teams](../resources/Teams.md)
**Delete a team**
**Operation ID:** `deleteTeam`

Remove an existing team.

Succeeds only if the team has no associated Escalation Policies, Services, Schedules and Subteams.

All associated unresovled incidents will be reassigned to another team (if specified) or will loose team association, thus becoming account-level (with visibility implications).

Note that the incidents reassignment process is asynchronous and has no guarantee to complete before the API call return.

A team is a collection of Users and Escalation Policies that represent a group of people within an organization.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#teams)

Scoped OAuth requires: `teams.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The team was deleted successfully. |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

