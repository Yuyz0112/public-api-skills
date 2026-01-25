# GET /teams

**Resource:** [Teams](../resources/Teams.md)
**List teams**
**Operation ID:** `listTeams`

List teams of your PagerDuty account, optionally filtered by a search query.

A team is a collection of Users and Escalation Policies that represent a group of people within an organization.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#teams)

Scoped OAuth requires: `teams.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A paginated array of teams. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

