# PUT /teams/{id}/escalation_policies/{escalation_policy_id}

**Resource:** [Teams](../resources/Teams.md)
**Add an escalation policy to a team**
**Operation ID:** `updateTeamEscalationPolicy`

Add an escalation policy to a team.

A team is a collection of Users and Escalation Policies that represent a group of people within an organization.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#teams)

Scoped OAuth requires: `teams.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The escalation policy was added to the team. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

